---
title: "music"
layout: collection
permalink: /music/
author_profile: true
---

<div class="section-nav portfolio-nav">
  <div class="section-nav__brand">portfolio</div>
  <nav class="section-nav__links">
    <a href="/home/">home</a>
    <a href="/art/">art</a>
    <a href="/music/">music</a>
    <a href="/other/">other stuff</a>
    <a href="/artabout/">about</a>
    <a href="/professional/" class="section-nav__button">professional</a>
  </nav>
</div>

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
