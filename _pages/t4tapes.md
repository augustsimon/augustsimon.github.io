---
layout: single
classes: wide
permalink: /t4tapes/
title: "t4tapes"
author_profile: false
---

t4tapes is a tape cassette compilation recorded by and for trans people. we recorded straight to tape in our friends' basement in bushwick, ny, and mixed, mastered, duplicated, and distributed in-house. we recorded 12 bands or solo artists on volume 1, and 22 on volume 2.

our two missions in this were to:
1. give recording access to musicians that might not have had it otherwise. recording space in nyc can be financially prohibitive, we wanted to let as many people in on it as we could. we also gave a bunch of free tapes to each band, to sell as merch and hopefully offset future band expenses. we wanted to show people how accessible this type of recording is, destigmatizing "shitty recording quality" and how that can perpetuate into shame about posting unpolished works. we could only record one solid take, and leaned into the imperfections. you can do the same thing at home with a voice memo! just post your song just post it :)
2. archive and catalogue trans voices in the nyc area, at this specific point in time. there is a really important integration of punk and folk and advocacy/activism happening in the queerpunk scene, especially in the midst of fascism and debilitating disease. it's important to us that we preserved our art in a physical way that isn't reliant on digital media conglomerates affording/remembering to pay their digital lease, or revoke access to our own art because of a shift in power. but instead we want to have it in a form we can hold and bring with us and show to each other for a long time.

i feel very proud to be a part of this project! we all did a little bit of everything, but i focused on the graphic design.

---

## Volume I

<div class="media-row">
  
  <div class="media-column image-side">
    <img src="/assets/images/t4tapes/t4t1-tapelabel.png" alt="t4tapes vol 1 tape label" class="portfolio-media-img">
    <p class="caption">stickers i made to label side a and b of the tapes, with artist names</p>
  </div>

  <div class="media-column player-side">
    <p class="project-desc">we made this!</p>
    <!-- Updated src with artwork=small -->
    <iframe class="bandcamp-embed" src="https://bandcamp.com/EmbeddedPlayer/album=281724953/size=large/bgcol=333333/linkcol=fe7eaf/artwork=small/transparent=true/" seamless>
      <a href="https://t4tapes.bandcamp.com/album/t4tapes-basement-sessions">T4Tapes: Basement Sessions by T4Tapes</a>
    </iframe>
  </div>

</div>

## Volume II

<div class="media-row">
  
  <div class="media-column player-side">
    <p class="project-desc">description of vol 2</p>
    <!-- Updated src with artwork=small -->
    <iframe class="bandcamp-embed" src="https://bandcamp.com/EmbeddedPlayer/album=281724953/size=large/bgcol=333333/linkcol=fe7eaf/artwork=small/transparent=true/" seamless>
    </iframe>
  </div>

  <div class="media-column image-side">
    <img src="/assets/images/digitalart/sleepyinthemeadow.jpeg" alt="t4tapes Volume 2 Cover Art" class="portfolio-media-img">
    <p class="caption">vol 2 description</p>
  </div>

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

  /* --- SECTION HEADINGS --- */
  h2 {
    font-size: 2.2rem !important;
    margin-top: 3rem !important;
    margin-bottom: 1.5rem !important;
    border-bottom: 1px solid #eee;
    padding-bottom: 0.5rem;
  }

  /* --- MULTIMEDIA SPLIT ROW SYSTEM --- */
  .media-row {
    display: flex;
    flex-direction: row;
    gap: 3rem; /* Space between columns */
    align-items: flex-start; /* ⬅️ Changed to flex-start so images don't stretch */
    width: 100%;
    margin-bottom: 5rem; /* Generous gap before the next Volume */
  }

  .media-column {
    flex: 1; /* Splits space 50/50 */
    min-width: 0;
  }

  /* Image Column Layout */
  .image-side {
    display: flex;
    flex-direction: column;
  }

  /* Portfolio Image styling */
  .portfolio-media-img {
    width: 100%;
    height: auto;
    border-radius: 6px;
    box-shadow: 0 8px 24px rgba(0, 0, 0, 0.15);
    object-fit: cover; /* Keeps image proportions clean */
  }

  /* Captions for photos */
  .caption {
    font-size: 0.9rem;
    color: #888;
    margin-top: 0.8rem;
    font-style: italic;
    line-height: 1.4;
  }

  /* Player Column Layout */
  .player-side {
    display: flex;
    flex-direction: column; /* Stacks description and player vertically */
    height: 100%;
  }

  .project-desc {
    font-size: 1.1rem;
    line-height: 1.6;
    margin-top: 0 !important;
    margin-bottom: 1.5rem !important;
  }

  /* Fixed Height Bandcamp Embed styling to display Art + Tracklist */
  .bandcamp-embed {
    border: 0;
    width: 100%;
    height: 700px !important; /* ⬅️ Gives 700px height to fit both art and scrollable tracklist */
  }

  /* --- MOBILE RESPONSIVE TWEAKS --- */
  @media (max-width: 900px) {
    .media-row {
      flex-direction: column !important; /* Stacks vertically on mobile */
      gap: 2rem;
      align-items: initial; /* Resets height stretch on mobile */
    }
    
    .media-column {
      width: 100%;
    }

    .bandcamp-embed {
      height: 600px !important; /* Slightly shorter, compact height for mobile screens */
    }
    
    /* Order fix for Volume 2 on mobile: image sits on top of player */
    .media-row:of-type(2) {
      display: flex;
      flex-direction: column-reverse !important;
    }
  }
</style>