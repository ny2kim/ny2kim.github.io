---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: /assets/pdf/CV_Nayeon_Kim.pdf
cv_updated: 2026-10-18
---
{% assign cv_pdf_url = page.cv_pdf | relative_url %}
<style>
  h1.post-title {
    display: none;
  }


  .cv-container {
    width: 100%;
    height: 1000px; 
    border: 1px solid #ddd;
  }

  .cv-button-container {
    margin-bottom: 1rem;
    text-align: right;
  }
  

  .desktop-pdf { display: block; }
  .mobile-pdf { display: none; }
  
  @media only screen and (max-width: 1024px) {
    .desktop-pdf { display: none; }
    .mobile-pdf { display: block; }
  }

</style>

<h1>Nayeon Kim – CV</h1>

<p><em>Last updated: {{ page.cv_updated | date: "%b %d, %Y" }}</em></p>

<div class="cv-button-container">
  <a href="{{ cv_pdf_url }}" target="_blank" rel="noopener noreferrer" class="btn z-depth-0" role="button">
    <i class="fas fa-file-pdf"></i> View PDF
  </a>
</div>

<div class="cv-container">
  <iframe class="desktop-pdf"
    src="{{ cv_pdf_url }}#toolbar=0&navpanes=0&view=FitH"
    width="100%"
    height="100%"
    style="border: none;">
  </iframe>
  
  <iframe class="mobile-pdf"
    src="{{ cv_pdf_url }}#toolbar=0&navpanes=0&view=FitH"
    width="100%"
    height="100%"
    style="border: none;">
  </iframe>
</div>

