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

  .pdf-container {
    width: 100%;
    height: 1000px;
    border: none;
    overflow: auto;
    -webkit-overflow-scrolling: touch;
  }
  
  @media (max-width: 768px) {
    .pdf-container {
      height: 80vh; 
      min-height: 600px;
    }
    
    .pdf-fallback {
      display: block;
    }
  }
  
</style>

<h1>Nayeon Kim – CV</h1>

<p><em>Last updated: {{ site.time | date: "%b %d, %Y" }}</em></p>

<iframe
  src="/assets/pdf/Nayeon_Kim_CV_250724.pdf#toolbar=0&navpanes=0&view=FitH"
  width="100%"
  height="1000px"
  style="border: none;"
></iframe>
