---
layout: single
classes: wide
permalink: /posters/
title: "posters"
author_profile: false
---


<!-- blixfest -->
<div class="side-by-side-row">
  <div class="side-by-side-col">
    <img src="/assets/images/posters/blixfestposter1.png" alt="blixworld fest lineup" class="portfolio-media-img">
    <p class="caption">blixfest lineup</p>
  </div>

  <div class="side-by-side-col">
    <img src="/assets/images/posters/blixfestposter3.png" alt="blixworld fest vendors" class="portfolio-media-img">
    <p class="caption">blixworld fest vendor poster</p>
  </div>
</div>

<!-- blix sched -->
<div class="single-image-wrapper">
  <img src="/assets/images/posters/blixfestposter2.png" alt="blixworld fest schedule" class="portfolio-media-img">
  <p class="caption">blixworld fest schedule</p>
</div>

<!-- cherry + bread -->
<div class="side-by-side-row">
  <div class="side-by-side-col">
    <img src="/assets/images/posters/cherry debut poster.PNG" alt="cherrypicking debut" class="portfolio-media-img">
    <p class="caption">cherrypicking debut</p>
  </div>

  <div class="side-by-side-col">
    <img src="/assets/images/posters/breadandroses.jpeg" alt="bluestockings show" class="portfolio-media-img">
    <p class="caption">bluestockings show</p>
  </div>
</div>

<!-- solstice -->
<div class="three-up-row">
  <div class="three-up-col">
    <img src="/assets/images/posters/wintersolstice.png" alt="winter solstice" class="portfolio-media-img">
    <p class="caption">winter solstice</p>
  </div>

  <div class="three-up-col">
    <img src="/assets/images/posters/summersolstice.png" alt="summer solstice artists" class="portfolio-media-img">
    <p class="caption">summer solstice artists</p>
  </div>

  <div class="three-up-col">
    <img src="/assets/images/posters/summersolstice2.png" alt="summer solstice vendors" class="portfolio-media-img">
    <p class="caption">summer solstice vendors</p>
  </div>
</div>

<!-- Row 3 -->
<div class="side-by-side-row">
  <div class="side-by-side-col">
    <img src="/assets/images/posters/avataredenflyer.png" alt="avatar eden tour" class="portfolio-media-img">
    <p class="caption">avatar eden tour</p>
  </div>

  <div class="side-by-side-col">
    <img src="/assets/images/posters/pigeonpack.jpeg" alt="pigeon pack show" class="portfolio-media-img">
    <p class="caption">pigeon pack show</p>
  </div>
</div>

<!-- Row 4 -->
<div class="side-by-side-row">
  <div class="side-by-side-col">
    <img src="/assets/images/posters/rooftopposter.png" alt="show on my roof" class="portfolio-media-img">
    <p class="caption">show on my roof</p>
  </div>

  <div class="side-by-side-col">
    <img src="/assets/images/posters/claymommy.PNG" alt="clay mommy play" class="portfolio-media-img">
    <p class="caption">clay mommy play</p>
  </div>
</div>

<!-- aug in jan -->
<div class="single-image-wrapper">
  <img src="/assets/images/posters/august in january.png" alt="august in january schedule" class="portfolio-media-img">
  <p class="caption">august in january schedule</p>
</div>


<style>
  /* --- LAYOUT CONFIG (Left-Aligned Wide Page) --- */
  @media (min-width: 64em) {
    .archive, .page {
      width: 100% !important;
      padding-left: 5% !important;
      padding-right: 5% !important;
      margin-right: 0 !important;
      float: left !important; 
    }
    .page__content {
      width: 100% !important;
      max-width: 100% !important;
    }
  }

/* --- SINGLE CENTERED IMAGE SYSTEM --- */
  .single-image-wrapper {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-left: auto;
    margin-right: auto;
    max-width: 650px; /* Controls max size on desktop so it doesn't stretch huge */
    width: 100%;
    margin-bottom: 4rem;
    text-align: center;
  }

  /* --- SIDE-BY-SIDE EQUAL SIZE SYSTEM --- */
  .side-by-side-row {
    display: flex;
    flex-direction: row;
    gap: 2rem; /* Spacing between the two images */
    width: 100%;
    margin-bottom: 4rem;
  }

  .side-by-side-col {
    flex: 1; /* Forces both containers to take up exactly 50% width */
    min-width: 0;
    display: flex;
    flex-direction: column;
  }

  /* --- 3-UP SIDE-BY-SIDE EQUAL SIZE SYSTEM --- */
  .three-up-row {
    display: flex;
    flex-direction: row;
    gap: 1.5rem; /* Spacing between the three images */
    width: 100%;
    margin-bottom: 4rem;
  }

  .three-up-col {
    flex: 1; /* Forces all three containers to split width equally (33.3% each) */
    min-width: 0;
    display: flex;
    flex-direction: column;
  }

  /* Portfolio Image styling */
  .portfolio-media-img {
    width: 100%;
    height: auto;
    border-radius: 6px;
    box-shadow: 0 8px 24px rgba(0, 0, 0, 0.15);
    object-fit: cover;
  }

  /* Captions for photos */
  .caption {
    font-size: 0.9rem;
    color: #888;
    margin-top: 0.8rem;
    font-style: italic;
    line-height: 1.4;
    width: 100%;
  }

  /* --- MOBILE RESPONSIVE TWEAKS --- */
  @media (max-width: 900px) {
    /* Stack side-by-side images vertically on mobile */
    .side-by-side-row {
      flex-direction: column !important;
      gap: 2rem;
    }
  }
</style>

```