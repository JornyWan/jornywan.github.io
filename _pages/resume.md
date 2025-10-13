---
layout: page
permalink: /resume/
title: resume
description: My curriculum vitae and professional resume.
nav: true
nav_order: 6
---

<div class="resume-container" style="text-align: center; margin: 20px 0;">
  <p>Click below to view or download my resume:</p>
  <a href="{{ '/assets/pdf/resume.pdf' | relative_url }}" target="_blank" class="btn btn-primary">
    <i class="fas fa-file-pdf"></i> View Resume (PDF)
  </a>
</div>

<div class="pdf-embed" style="margin-top: 30px;">
  <embed src="{{ '/assets/pdf/resume.pdf' | relative_url }}" type="application/pdf" width="100%" height="800px" />
</div>

<style>
  .btn-primary {
    display: inline-block;
    padding: 12px 24px;
    background-color: #007bff;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-weight: 500;
    transition: background-color 0.3s;
  }
  
  .btn-primary:hover {
    background-color: #0056b3;
    color: white;
    text-decoration: none;
  }
  
  .btn-primary i {
    margin-right: 8px;
  }
</style>
