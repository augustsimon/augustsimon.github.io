---
title: "portfolio"
permalink: /portfolio/
layout: single
classes: wide
author_profile: true
---

<div class="section-nav portfolio-nav">
  <div class="section-nav__brand">portfolio</div>
  <nav class="section-nav__links">
    <a href="/home/">home</a>
    <a href="/art/">art</a>
    <a href="/music/">music</a>
    <a href="/other/">other stuff</a>
    <a href="/about/">about</a>
    <a href="/professional/" class="section-nav__button">professional</a>
  </nav>
</div>

welcome! this is my repository for music, art, and other stuff that i want to keep track of. you can navigate thru categories using the links above ^. each one has different collections to explore.

<!-- gallery scroll box -->
<div class="scroll-gallery-container">
  <div class="scroll-gallery-track">
    <div class="scroll-slide"><img src="/assets/images/digitalart/lenas-universe.jpg" alt="Lena's Universe"></div>
    <div class="scroll-slide"><img src="/assets/images/digitalart/sleepyinthemeadow.jpeg" alt="Sleepy in the Meadow"></div>
    <div class="scroll-slide"><img src="/assets/images/digitalart/salome-norah.png" alt="The Trickster"></div>
    <div class="scroll-slide"><img src="/assets/images/digitalart/Pupsaroundtheworld.png" alt="Pups Around the World"></div>
    
    <div class="scroll-slide"><img src="/assets/images/digitalart/lenas-universe.jpg" alt="Lena's Universe"></div>
    <div class="scroll-slide"><img src="/assets/images/digitalart/sleepyinthemeadow.jpeg" alt="Sleepy in the Meadow"></div>
    <div class="scroll-slide"><img src="/assets/images/digitalart/salome-norah.png" alt="The Trickster"></div>
    <div class="scroll-slide"><img src="/assets/images/digitalart/Pupsaroundtheworld.png" alt="Pups Around the World"></div>

    <div class="scroll-slide"><img src="/assets/images/digitalart/lenas-universe.jpg" alt="Lena's Universe"></div>
    <div class="scroll-slide"><img src="/assets/images/digitalart/sleepyinthemeadow.jpeg" alt="Sleepy in the Meadow"></div>
    <div class="scroll-slide"><img src="/assets/images/digitalart/salome-norah.png" alt="The Trickster"></div>
    <div class="scroll-slide"><img src="/assets/images/digitalart/Pupsaroundtheworld.png" alt="Pups Around the World"></div>
  </div>
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

.scroll-gallery-container {
  overflow: hidden;
  width: 100%;
  margin: 2em 0;
  position: relative;
}

.scroll-gallery-track {
  display: flex;
  width: max-content;
  animation: dynamic-scroll 35s linear infinite;
}

.scroll-slide {
  height: 400px;
  padding: 0 10px;
  flex-shrink: 0;
}

.scroll-slide img {
  height: 100%;
  width: auto;
  object-fit: contain;
  border-radius: 6px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
}

@keyframes dynamic-scroll {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(-33.3333%); 
  }
}

.scroll-gallery-container:hover .scroll-gallery-track {
  animation-play-state: paused;
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