---
layout: single
classes: wide
permalink: /professional/
title: "professional"
author_profile: true
---

<div class="section-nav professional-nav">
  <div class="section-nav__brand">professional</div>
  <nav class="section-nav__links">
    <a href="#overview">overview</a>
    <a href="#experience">experience</a>
    <a href="#skills">skills</a>
    <a href="#resume">resume</a>
    <a href="/home/" class="section-nav__button">portfolio</a>
  </nav>
</div>

<section id="overview" class="profile-card">
  <h2>professional overview</h2>
  <p>i'm a multidisciplinary artist and creative professional with experience in visual design, communications, and collaborative media work. my practice brings together storytelling, visual systems, and community-centered projects that make complex ideas feel accessible.</p>
</section>

<section id="experience" class="experience-block">
  <h2>experience</h2>

  <div class="experience-item">
    <h3>visual designer / creative collaborator</h3>
    <p class="meta">freelance + community-based projects</p>
    <p>developed event graphics, digital art, social media visuals, and identity-focused work for arts organizations and independent music communities.</p>
  </div>

  <div class="experience-item">
    <h3>graphic design intern</h3>
    <p class="meta">the lgbt network</p>
    <p>designed promotional media and digital materials that supported outreach, engagement, and community-centered communication.</p>
  </div>

  <div class="experience-item">
    <h3>creative partner</h3>
    <p class="meta">gallim dance company</p>
    <p>contributed visual materials and branding-adjacent design support in service of public-facing programming and institutional storytelling.</p>
  </div>
</section>

<section id="skills" class="skills-block">
  <h2>skills</h2>
  <div class="tag-list">
    <span>graphic design</span>
    <span>brand identity</span>
    <span>visual storytelling</span>
    <span>art direction</span>
    <span>digital illustration</span>
    <span>social media design</span>
    <span>collaboration</span>
    <span>communication</span>
  </div>
</section>

<section id="resume" class="resume-block">
  <h2>resume</h2>
  <p>my background blends creative practice with community-facing work, and i'm especially interested in projects that connect culture, communication, and accessibility.</p>
  <p>for a more detailed summary of my work, feel free to contact me directly or explore the portfolio section for examples of my projects.</p>
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
  text-decoration: none;
  color: inherit;
  padding: 0.45rem 0.8rem;
  border-radius: 999px;
  transition: background 0.2s ease;
}

.section-nav__links a:hover {
  background: rgba(0, 0, 0, 0.05);
}

.section-nav__button {
  background: #111;
  color: #fff !important;
}

.profile-card,
.experience-block,
.skills-block,
.resume-block {
  margin: 1.5rem 0;
  padding: 1.5rem;
  background: rgba(0, 0, 0, 0.02);
  border: 1px solid rgba(0, 0, 0, 0.06);
  border-radius: 18px;
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
