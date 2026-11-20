---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div id="cv-viewer" class="cv-viewer" aria-label="Chidera M. Ejike CV">
  <p class="cv-loading">Loading CV…</p>
</div>

<script src="{{ base_path }}/assets/js/pdfjs/pdf.min.js"></script>
<script>
(function () {
  var url = "{{ base_path }}/files/Ejike_CV.pdf";
  var viewer = document.getElementById("cv-viewer");
  pdfjsLib.GlobalWorkerOptions.workerSrc = "{{ base_path }}/assets/js/pdfjs/pdf.worker.min.js";

  var pdfDoc = null, lastWidth = 0;

  function render() {
    var width = viewer.clientWidth;
    if (!pdfDoc || width === lastWidth) return;
    lastWidth = width;
    viewer.innerHTML = "";
    var ratio = window.devicePixelRatio || 1;
    var chain = Promise.resolve();
    for (var n = 1; n <= pdfDoc.numPages; n++) {
      (function (num) {
        var canvas = document.createElement("canvas");
        canvas.className = "cv-page";
        viewer.appendChild(canvas);
        chain = chain.then(function () {
          return pdfDoc.getPage(num).then(function (page) {
            var base = page.getViewport({ scale: 1 });
            var vp = page.getViewport({ scale: (width / base.width) * ratio });
            canvas.width = vp.width;
            canvas.height = vp.height;
            return page.render({ canvasContext: canvas.getContext("2d"), viewport: vp }).promise;
          });
        });
      })(n);
    }
  }

  pdfjsLib.getDocument(url).promise.then(function (doc) {
    pdfDoc = doc;
    render();
  }).catch(function () {
    viewer.innerHTML = '<p class="cv-loading">The CV could not be loaded. Please refresh the page.</p>';
  });

  var timer;
  window.addEventListener("resize", function () {
    clearTimeout(timer);
    timer = setTimeout(render, 250);
  });

  viewer.addEventListener("contextmenu", function (e) { e.preventDefault(); });
})();
</script>
