---
layout: cv
permalink: /cv/
title: Curriculum Vitae
nav: true
nav_order: 1
cv_pdf: cv.pdf
---

<!-- Display the PDF CV on the website page -->

<div class="cv-actions">
  <a class="btn btn-primary" href="{{ '/assets/pdf/cv.pdf' | relative_url }}" download>
    Download CV
  </a>
</div>

<div class="cv-frame-wrap">
  <div class="cv-topbar"></div>
  <object class="cv-object"
          data="{{ '/assets/pdf/cv.pdf' | relative_url }}#view=FitH"
          type="application/pdf">
    <iframe class="cv-iframe"
            src="{{ '/assets/pdf/cv.pdf' | relative_url }}#view=FitH">
    </iframe>
  </object>
  <p class="cv-fallback">
    Your browser can’t display PDFs. 
    <a href="{{ '/assets/pdf/cv.pdf' | relative_url }}">Open the CV</a>.
  </p>
</div>
