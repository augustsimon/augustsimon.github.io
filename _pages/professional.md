---
layout: single
classes: wide
permalink: /professional/
title: "Professional Experience"
author_profile: true
---

<div class="section-nav professional-nav">
  <div class="section-nav__brand">Navigation</div>
  <nav class="section-nav__links">
    <a href="/professional/" class="is-active" aria-current="page">Home</a>
    <a href="/resume/">Resume</a>
    <a href="/prior-events/">Public Speaking & Media</a>
  </nav>
</div>

<section class="professional-intro">
  <p class="eyebrow">Welcome!</p>
  <h2>I'm an interdisciplinary social worker in pursuit of creating radical community care for the LGBTQ+ community and substance users.</h2>
  <p>I've worked in community organizing, substance abuse outpatient, direct support, and nonprofit. I'm hoping to build a practice interwoven with harm reduction, mutual aid, and radical liberation for all. My work is shaped by trauma-informed, anti-carceral firsthand experience battling bureaucratic systems as a marginalized person.</p>
  <div class="cta-row">
    <a href="/resume/" class="cta-button">View Resume</a>
    <a href="/prior-events/" class="cta-button secondary">See Public Speaking & Media</a>
  </div>
</section>

<section class="summary-grid">
  <div class="summary-card">
    <h3>Focus</h3>
    <p>Building & engaging in systems that promote liberation for marginalized people</p>
  </div>
  <div class="summary-card">
    <h3>Strengths</h3>
    <p>Pro-active & holistic problem solving, individualized treatment styles, dedication</p>
  </div>
  <div class="summary-card">
    <h3>Experience</h3>
    <p>Community organizing, substance abuse outpatient, direct support, and nonprofit</p>
  </div>
</section>

<style>
.section-nav { display: flex; flex-wrap: wrap; justify-content: space-between; align-items: center; gap: 1rem; padding: 0.9rem 1.25rem; margin: 0 0 1.5rem 0; border: 1px solid rgba(255, 255, 255, 0.8); border-radius: 999px; background: transparent; box-shadow: none; }

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

.section-nav__links a { text-decoration: none; color: inherit; padding: 0.45rem 0.8rem; border: 1px solid transparent; border-radius: 999px; transition: background 0.2s ease, border-color 0.2s ease; }

.section-nav__links a:hover { background: rgba(255, 255, 255, 0.1); border-color: rgba(255, 255, 255, 0.65); }

.section-nav__button { background: transparent; border: 1px solid rgba(255, 255, 255, 0.8); color: #fff !important; }

.section-nav .section-nav__links a.is-active { background: rgba(255, 255, 255, 0.12); border-color: rgba(255, 255, 255, 0.8); font-weight: 700; }

.professional-nav { background: transparent; border-color: rgba(255, 255, 255, 0.8); box-shadow: none; }

.professional-nav .section-nav__brand,
.professional-nav .section-nav__links a {
  color: #fff;
}

.professional-nav .section-nav__links a:hover { background: rgba(255, 255, 255, 0.1); border-color: rgba(255, 255, 255, 0.65); }

.professional-intro,
.profile-card,
.experience-block,
.skills-block,
.resume-block,
.summary-card {
  margin: 1.5rem 0;
  padding: 1.5rem;
  background: rgba(0, 0, 0, 0.02);
  border: 1px solid rgba(0, 0, 0, 0.06);
  border-radius: 18px;
}

.professional-intro {
  background: linear-gradient(135deg, rgba(17, 17, 17, 0.96), rgba(34, 34, 34, 0.9));
  color: #fff;
  padding: 2rem 1.75rem;
}

.eyebrow {
  margin: 0 0 0.75rem 0;
  font-size: 0.8rem;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  opacity: 0.75;
}

.professional-intro h2 {
  margin: 0 0 1rem 0;
  color: #fff;
  font-size: clamp(2rem, 3vw, 3rem);
  line-height: 1.2;
}

.cta-row {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
  margin-top: 1.5rem;
}

.cta-button {
  display: inline-block;
  text-decoration: none;
  background: #fff;
  color: #111;
  border-radius: 999px;
  padding: 0.8rem 1.2rem;
  font-weight: 700;
}

.cta-button.secondary {
  background: transparent;
  color: #fff;
  border: 1px solid rgba(255, 255, 255, 0.4);
}

.summary-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 1rem;
}

.summary-card h3 {
  margin-top: 0;
}

.experience-item {
  margin-bottom: 1.25rem;
  padding-bottom: 1rem;
  border-bottom: 1px solid rgba(0, 0, 0, 0.08);
}

.experience-item:last-child {
  margin-bottom: 0;
  padding-bottom: 0;
  border-bottom: none;
}

.meta {
  font-size: 0.85rem;
  letter-spacing: 0.06em;
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
}
</style>
