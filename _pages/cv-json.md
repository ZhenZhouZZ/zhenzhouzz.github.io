---
layout: archive
title: "CV"
permalink: /cv-json/
author_profile: false
redirect_from:
  - /resume-json
---

{% include base_path %}

<style>
  .archive {
    width: 100%;
    margin: 0;
    padding: 0;
  }
  
  .pdf-container {
    width: 100%;
    height: 85vh;
    margin-bottom: 20px;
  }
</style>

<object class="pdf-container" data="{{ base_path }}/files/My_CV.pdf" type="application/pdf">
  <p>Your browser doesn't support embedded PDFs. 
     <a href="{{ base_path }}/files/My_CV.pdf">Click here to download the PDF</a> instead.
  </p>
</object>

<div class="cv-download-links">
  <a href="{{ base_path }}/files/My_CV.pdf" class="btn btn--primary">Download CV as PDF</a>
  <a href="{{ base_path }}" class="btn btn--inverse">View Markdown CV</a>
</div>