---
layout: single
classes: wide
permalink: /art/
title: "art"
author_profile: true
---

below, you can find my visual art divided into categories

<div class="collection-button-container">

  <a href="/t4tapes/" class="collection-btn" style="background-image: url('/assets/images/t4tzine-4-5.png');">
    <div class="collection-text-wrapper">
      <h2 class="collection-title">T4Tapes</h2>
      <p class="collection-desc">cassette compilation recorded straight to tape by and for trans ppl</p>
    </div>
  </a>

  <a href="/posters/" class="collection-btn" style="background-image: url('/assets/images/avataredenflyer.png');">
    <div class="collection-text-wrapper">
      <h2 class="collection-title">posters</h2>
      <p class="collection-desc">past efforts to get you to come to the gig</p>
    </div>
  </a>

  <a href="/physicalmedia/" class="collection-btn" style="background-image: url('/assets/images/cherryjcard.PNG');">
    <div class="collection-text-wrapper">
      <h2 class="collection-title">physical music media</h2>
      <p class="collection-desc">zines, j-cards, t-shirt designs, and other things that were designed with the intention to hold</p>
    </div>
  </a> 
  
   <a href="/digitalart/" class="collection-btn" style="background-image: url('/assets/images/lenas-universe.jpg');">
    <div class="collection-text-wrapper">
      <h2 class="collection-title">digital art</h2>
      <p class="collection-desc">art i made on a small computer</p>
    </div>
  </a>

  <a href="/traditionalart/" class="collection-btn" style="background-image: url('/assets/images/spiritcircle.png');">
    <div class="collection-text-wrapper">
      <h2 class="collection-title">traditional art</h2>
      <p class="collection-desc">art made on paper with physical materials</p>
    </div>
  </a>

  <a href="/logosncovers/" class="collection-btn" style="background-image: url('/assets/images/crushfundpink.png');">
    <div class="collection-text-wrapper">
      <h2 class="collection-title">logos & album covers</h2>
      <p class="collection-desc">branding-adjacent work for local bands</p>
    </div>
  </a>

  <a href="/gallim/" class="collection-btn" style="background-image: url('/assets/images/gallimspread1.png');">
    <div class="collection-text-wrapper">
      <h2 class="collection-title">GALLIM Dance Company</h2>
      <p class="collection-desc">my work with GALLIM, a nonprofit dance company</p>
    </div>
  </a>

  <a href="/lgbtnetwork/" class="collection-btn" style="background-image: url('/assets/images/tgncconnect.jpg');">
    <div class="collection-text-wrapper">
      <h2 class="collection-title">The LGBT Network</h2>
      <p class="collection-desc">some graphics i made during my internship with them</p>
    </div>
  </a>

</div>

### Other Projects & Sketches
Feel free to drop me a line if you have questions about commission work or prints.


<style>
/* 1. Flexbox layout to make buttons stack neatly */
.collection-button-container {
  display: flex;
  flex-direction: column;
  gap: 1.5em; /* Space between each collection banner */
  width: 100%;
  margin: 2em 0;
}

/* 2. Large banner buttons */
.collection-btn {
  display: flex;
  justify-content: flex-start; /* Aligns text wrapper to the left side */
  align-items: center; /* Centers text vertically */
  text-decoration: none !important; /* Disables standard link underlines */
  height: 350px; /* ⬅️ Adjust this to make the banners taller or shorter */
  width: 100%;
  
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  
  border-radius: 8px; /* Slightly rounded edges for a clean modern look */
  transition: transform 0.25s ease, box-shadow 0.25s ease;
  overflow: hidden;
  position: relative;
}

/* 3. Dark overlay behind text so it remains readable regardless of image colors */
.collection-btn::before {
  content: '';
  position: absolute;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background: rgba(0, 0, 0, 0.45); /* Adjust opacity (0.1 to 1.0) */
  z-index: 1;
  transition: background 0.25s ease;
}

/* 4. Text container styling */
.collection-text-wrapper {
  color: white !important;
  max-width: 60%;
  padding-left: 2.5rem; /* Space from the left edge of the banner */
  z-index: 2; /* Sits above the dark background filter */
  position: relative;
}

.collection-title {
  margin: 0 !important;
  padding: 0;
  color: white !important;
  font-size: 2.5rem !important; /* Adjust font size of headings */
  font-weight: 700;
  text-transform: capitalize;
  text-shadow: 0 2px 8px rgba(0, 0, 0, 0.6);
}

.collection-desc {
  margin: 0.5em 0 0 0 !important;
  color: #f0f0f0 !important;
  font-size: 1.1rem;
  font-weight: 400;
  text-shadow: 0 1px 4px rgba(0, 0, 0, 0.6);
  opacity: 0.9;
}

/* 5. Sleek Hover Effects */
.collection-btn:hover {
  transform: translateY(-3px); /* Subtle lift on hover */
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2); /* Deepens shadow */
}

.collection-btn:hover::before {
  background: rgba(0, 0, 0, 0.35); /* Brightens image slightly on hover */
}
</style>