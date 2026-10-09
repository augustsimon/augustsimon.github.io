---
title: "music"
layout: collection
permalink: /music/
author_profile: true
---

<div class="section-nav portfolio-nav">
  <div class="section-nav__brand">navigation</div>
  <nav class="section-nav__links">
    <a href="/home/">home</a>
    <a href="/art/">art</a>
    <a href="/music/" class="is-active" aria-current="page">music</a>
    <a href="/other/">other stuff</a>
    <a href="/artabout/">about</a>
  </nav>
</div>

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

.section-nav .section-nav__links a.is-active { background: rgba(255, 255, 255, 0.12); border-color: rgba(255, 255, 255, 0.8); font-weight: 700; }

.section-nav__button { background: transparent; border: 1px solid rgba(255, 255, 255, 0.8); color: #fff !important; }

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
