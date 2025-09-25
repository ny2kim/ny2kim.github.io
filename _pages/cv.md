---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
---
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

<p><em>Last updated: {{ site.time | date: "%b %d, %Y" }}</em></p>

<div class="cv-button-container">
  <a href="https://drive.google.com/file/d/1oKidZqt6bpsluqJHtWZM7Xa5NQfFaM_y/view?usp=drivesdk" target="_blank" class="btn z-depth-0" role="button">
    <i class="fas fa-file-pdf"></i> View on Google Drive
  </a>
</div>

<div class="cv-container">
  <iframe class="desktop-pdf"
    src="/assets/pdf/Nayeon_Kim_CV_250724.pdf#toolbar=0&navpanes=0&view=FitH"
    width="100%"
    height="100%"
    style="border: none;">
  </iframe>
  
  <iframe class="mobile-pdf"
    src="https://drive.google.com/file/d/1oKidZqt6bpsluqJHtWZM7Xa5NQfFaM_y/preview"
    width="100%"
    height="100%"
    style="border: none;">
  </iframe>
</div>
