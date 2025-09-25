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
    position: relative;
    width: 100%;
    overflow: auto;
    -webkit-overflow-scrolling: touch; 
    border: 1px solid
    height: 1000px; 
  }
  .cv-iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: none;
  }
  .cv-button-container {
    margin-bottom: 1rem;
    text-align: right;
  }
</style>

<h1>Nayeon Kim – CV</h1>

<p><em>Last updated: {{ site.time | date: "%b %d, %Y" }}</em></p>

<div class="cv-button-container">
  <a href="https://drive.google.com/file/d/1oKidZqt6bpsluqJHtWZM7Xa5NQfFaM_y/view?usp=drivesdk" target="_blank" class="btn btn-sm z-depth-0" role="button">
    <i class="fas fa-file-pdf"></i> View on Google Drive
  </a>
</div>

<div class="cv-container">
  <iframe
    src="/assets/pdf/Nayeon_Kim_CV_250724.pdf#toolbar=0&navpanes=0&view=FitH"
    class="cv-iframe"
  ></iframe>
</div>
