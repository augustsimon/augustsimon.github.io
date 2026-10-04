---
layout: single
classes: wide
permalink: /resume/
title: "resume"
author_profile: true
---

<div class="section-nav professional-nav">
  <div class="section-nav__brand">professional</div>
  <nav class="section-nav__links">
    <a href="/professional/">home</a>
    <a href="/resume/">resume</a>
    <a href="/prior-events/">prior events</a>
  </nav>
</div>

<section class="resume-page">
  <header class="resume-header">
    <p class="eyebrow">resume</p>
    <h2>august simon</h2>
    <p>visual designer • artist • creative collaborator</p>
  </header>

  <div class="resume-block">
    <h3>profile</h3>
    <p>multidisciplinary creative with experience in visual design, art production, community engagement, and collaborative storytelling. work centers around accessible visual communication, strong design systems, and creative projects that connect people with culture and ideas.</p>
  </div>

  <div class="resume-block">
    <h3>experience</h3>

    <div class="resume-item">
      <div class="resume-meta">
        <h4>visual designer / creative collaborator</h4>
        <span>freelance + community-based work</span>
      </div>
      <p>developed event graphics, digital illustration, and visual materials for independent arts communities and local creative initiatives, with an emphasis on brand clarity and audience engagement.</p>
    </div>

    <div class="resume-item">
      <div class="resume-meta">
        <h4>graphic design intern</h4>
        <span>the LGBT network</span>
      </div>
      <p>designed outreach and promotional materials to support community engagement and communication across digital and print channels.</p>
    </div>

    <div class="resume-item">
      <div class="resume-meta">
        <h4>creative partner</h4>
        <span>gallim dance company</span>
      </div>
      <p>contributed visual assets and branding-adjacent design support for public-facing projects and storytelling materials.</p>
    </div>
  </div>

  <div class="resume-block">
    <h3>education</h3>
    <div class="resume-item">
      <div class="resume-meta">
        <h4>b.a. in art history</h4>
        <span>suny purchase</span>
      </div>
    </div>
  </div>

  <div class="resume-block">
    <h3>skills</h3>
    <div class="tag-list">
      <span>graphic design</span>
      <span>digital illustration</span>
      <span>brand identity</span>
      <span>visual storytelling</span>
      <span>art direction</span>
      <span>social media design</span>
      <span>collaboration</span>
      <span>communication</span>
    </div>
  </div>
</section>

<style>
.section-nav {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  gap: 1rem;
  padding: 0.9rem 1.25rem;
  margin: 0 0 1.5rem 0;
  border: 1px solid rgba(0, 0, 0, 0.08);
  border-radius: 999px;
  background: rgba(255, 255, 255, 0.7);
  box-shadow: 0 4px 18px rgba(0, 0, 0, 0.06);
}

.section-nav__brand {
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  font-size: 0.8rem;
}

.section-nav__links {
  display: flex;
  flex-wrap: wrap;
  justify-content: flex-end;
  gap: 0.8rem;
  align-items: center;
}

.section-nav__links a {
  color: inherit;
  text-decoration: none;
  padding: 0.45rem 0.8rem;
  border-radius: 999px;
  transition: background 0.2s ease;
}

.section-nav__links a:hover {
  background: rgba(0, 0, 0, 0.05);
}

.professional-nav {
  background: #111;
  border-color: rgba(255, 255, 255, 0.12);
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.18);
}

.professional-nav .section-nav__brand,
.professional-nav .section-nav__links a {
  color: #fff;
}

.professional-nav .section-nav__links a:hover {
  background: rgba(255, 255, 255, 0.12);
}

.resume-page {
  margin-top: 1rem;
}

.resume-header {
  margin-bottom: 1.5rem;
}

.resume-header h2 {
  margin: 0.25rem 0;
  font-size: clamp(2.1rem, 4vw, 3rem);
}

.resume-block {
  margin: 1.5rem 0;
  padding: 1.5rem;
  background: rgba(0, 0, 0, 0.02);
  border: 1px solid rgba(0, 0, 0, 0.06);
  border-radius: 18px;
}

.resume-item {
  margin-top: 1rem;
  padding-top: 1rem;
  border-top: 1px solid rgba(0, 0, 0, 0.08);
}

.resume-item:first-of-type {
  margin-top: 0.5rem;
  border-top: none;
  padding-top: 0;
}

.resume-meta {
  display: flex;
  justify-content: space-between;
  gap: 1rem;
  flex-wrap: wrap;
  margin-bottom: 0.4rem;
}

.resume-meta h4 {
  margin: 0;
}

.resume-meta span {
  font-size: 0.85rem;
  letter-spacing: 0.04em;
  text-transform: uppercase;
  opacity: 0.7;
}

.eyebrow {
  margin: 0;
  font-size: 0.8rem;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  opacity: 0.7;
}

.tag-list {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
}

.tag-list span {
  display: inline-block;
  padding: 0.5rem 0.9rem;
  border-radius: 999px;
  background: #111;
  color: #fff;
  font-size: 0.9rem;
}

@media (max-width: 768px) {
  .section-nav {
    border-radius: 1rem;
    align-items: flex-start;
  }

  .section-nav__links {
    justify-content: flex-start;
  }

  .resume-meta {
    flex-direction: column;
  }
}
</style>
