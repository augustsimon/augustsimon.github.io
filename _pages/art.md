---
layout: single
classes: wide
permalink: /art/
title: "art"
author_profile: true
---

below, you can find my visual art divided into categories

<div class="collection-button-container">

  <a href="/t4tapes/" class="collection-btn" style="background-image: url('/assets/images/t4t2-jcard-side-b.jpeg');">
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
/* 1. Grid layout - 2 columns on desktop, 1 column on mobile */
.collection-button-container {
  display: grid;
  grid-template-columns: repeat(2, 1fr); /* Creates 2 equal-width columns */
  gap: 1.0em; /* Space between each collection banner */
  width: 100%;
  margin: 1.5em 0;
}

/* 2. Large banner buttons */
.collection-btn {
  display: flex;
  justify-content: flex-start; /* Aligns text wrapper to the left side */
  align-items: center; /* Centers text vertically */
  text-decoration: none !important; /* Disables standard link underlines */
  height: 300px; /* ⬅️ Slightly shorter height looks better in a 2-column grid */
  width: 100%;
  
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  
  border-radius: 8px; /* Slightly rounded edges */
  transition: transform 0.25s ease, box-shadow 0.25s ease;
  overflow: hidden;
  position: relative;
}

/* 3. Dark overlay behind text for readability */
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
  max-width: 85%; /* ⬅️ Increased to 85% so text has room in narrower columns */
  padding-left: 2rem; /* Space from the left edge of the banner */
  padding-right: 2rem; /* Safety padding on the right */
  z-index: 2; /* Sits above the dark background filter */
  position: relative;
}

.collection-title {
  margin: 0 !important;
  padding: 0;
  color: white !important;
  font-size: 2.2rem !important; /* ⬅️ Slightly smaller font so it fits 2-column layout */
  font-weight: 700;
  text-transform: capitalize;
  text-shadow: 0 2px 8px rgba(0, 0, 0, 0.6);
}

.collection-desc {
  margin: 0.5em 0 0 0 !important;
  color: #f0f0f0 !important;
  font-size: 1.05rem;
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

/* 6. RESPONSIVE MOBILE FIX */
/* When the screen is 768px wide or smaller (like tablets and phones) */
@media (max-width: 768px) {
  .collection-button-container {
    grid-template-columns: 1fr; /* Collapse back down to a single column */
  }
  
  .collection-btn {
    height: 250px; /* Slightly shorter banners on mobile so they don't eat the screen */
  }

  .collection-title {
    font-size: 1.8rem !important; /* Smaller text for mobile screens */
  }
}
</style>