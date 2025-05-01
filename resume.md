---
layout: page
title: Resume
permalink: /resume/
---

<link rel="stylesheet" href="{{ '/assets/css/timeline.css' | relative_url }}">

# Curriculum Vitae

<div class="pdf-download">
  <a href="{{ '/assets/files/Ayush_Jain_Resume_2025.pdf' | relative_url }}" target="_blank" class="pdf-button">
    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" viewBox="0 0 16 16" style="margin-right: 5px;">
      <path d="M8 2a5.53 5.53 0 0 0-3.594 1.342c-.766.66-1.321 1.52-1.464 2.383C1.266 6.095 0 7.555 0 9.318 0 11.366 1.708 13 3.781 13h8.906C14.502 13 16 11.57 16 9.773c0-1.636-1.242-2.969-2.834-3.194C12.923 3.999 10.69 2 8 2zm2.354 6.854-2 2a.5.5 0 0 1-.708 0l-2-2a.5.5 0 1 1 .708-.708L7.5 9.293V5.5a.5.5 0 0 1 1 0v3.793l1.146-1.147a.5.5 0 0 1 .708.708z"/>
    </svg>
    Download Complete Resume (PDF)
  </a>
</div>

<div class="cv-section">
  <h2>Experience Timeline</h2>

  <!-- The Timeline -->
  <ul class="timeline">
    {% for exp in site.data.experience.experiences %}
    <li>
      <div class="direction-{% cycle 'l', 'r' %}">
        <div class="flag-wrapper">
          <span class="flag">{{ exp.place }}</span>
          <span class="time-wrapper"><span class="time">{{ exp.time }}</span></span>
        </div>
        <div class="desc">
          <b>{{ exp.title }}</b> <br/>
          <i>{{ exp.location }}</i> <br/>
          {{ exp.subtitle }}
        </div>
      </div>
    </li>
    {% endfor %}
  </ul>

  <h2>Education</h2>

  <!-- Education Timeline -->
  <ul class="timeline">
    {% for edu in site.data.education.education %}
    <li>
      <div class="direction-{% cycle 'l', 'r' %}">
        <div class="flag-wrapper">
          <span class="flag">{{ edu.place }}</span>
          <span class="time-wrapper"><span class="time">{{ edu.time }}</span></span>
        </div>
        <div class="desc">
          <b>{{ edu.title }}</b> <br/>
          <i>{{ edu.location }}</i> <br/>
          {{ edu.subtitle }}
        </div>
      </div>
    </li>
    {% endfor %}
  </ul>
</div>

<style>
  .pdf-download {
    text-align: center;
    margin: 20px 0 30px;
  }
  
  .pdf-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #3498db;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    transition: background-color 0.3s;
  }
  
  .pdf-button:hover {
    background-color: #2980b9;
    text-decoration: none;
    color: white;
  }
</style> 