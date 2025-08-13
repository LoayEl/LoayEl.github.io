---
layout: default
title: "Personal Site"
---

<div class="profile-section">
  <h1>{{ site.name }}</h1>
  <img src="{{ site.photo }}" alt="Photo of {{ site.name }}" width="180" class="profile-image" />
</div>

<div class="bio-section">
  {{ site.bio }}
</div>

<div class="links-section">
  <a href="{{ site.resume_url }}" class="link-card">
    <span class="link-icon">📄</span>
    <span class="link-text">Resume</span>
  </a>
  
  <a href="{{ site.linkedin_url }}" class="link-card" target="_blank">
    <span class="link-icon">💼</span>
    <span class="link-text">LinkedIn</span>
  </a>
  
  <a href="{{ site.github_url }}" class="link-card" target="_blank">
    <span class="link-icon">⚡</span>
    <span class="link-text">GitHub</span>
  </a>
</div>