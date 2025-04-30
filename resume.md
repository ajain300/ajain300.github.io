---
layout: page
title: Resume
permalink: /resume/
---

<link rel="stylesheet" href="{{ '/assets/css/timeline.css' | relative_url }}">

# Curriculum Vitae

<div class="cv-section">
  <p><a href="{{ '/assets/resume.pdf' | relative_url }}" target="_blank">Download Full CV (PDF)</a></p>

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