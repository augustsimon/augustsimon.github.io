---
title: "home"
permalink: /home/
layout: wide
author_profile: true
---

welcome! this is my repository for music, art, and other stuff that i want to keep track of. you can navigate thru categories using the links above ^. each one has different collections to explore.



/* gallery scroll box
<div class="scroll-gallery-container">
  <div class="scroll-gallery-track">
    <div class="scroll-slide"><img src="/assets/images/lenas-universe.jpg" alt="Lena's Universe"></div>
    <div class="scroll-slide"><img src="/assets/images/sleepyinthemeadow.jpeg" alt="Sleepy in the Meadow"></div>
    <div class="scroll-slide"><img src="/assets/images/salome-norah.png" alt="The Trickster"></div>
    <div class="scroll-slide"><img src="/assets/images/Pupsaroundtheworld.png" alt="Pups Around the World"></div>
    
    <div class="scroll-slide"><img src="/assets/images/lenas-universe.jpg" alt="Lena's Universe"></div>
    <div class="scroll-slide"><img src="/assets/images/sleepyinthemeadow.jpeg" alt="Sleepy in the Meadow"></div>
    <div class="scroll-slide"><img src="/assets/images/salome-norah.png" alt="The Trickster"></div>
    <div class="scroll-slide"><img src="/assets/images/Pupsaroundtheworld.png" alt="Pups Around the World"></div>
  </div>
</div>

<style>
.scroll-gallery-container {
  overflow: hidden;
  width: 100%;
  margin: 2em 0;
  position: relative;
}

.scroll-gallery-track {
  display: flex;
  width: max-content; /* Allows the track to expand infinitely based on image sizes */
  animation: dynamic-scroll 35s linear infinite;
}

.scroll-slide {
  /* We set a fixed height so they line up evenly, but leave width to automatic */
  height: 400px; /* ⬅️ Adjust this to make the whole row taller or shorter */
  padding: 0 10px; /* Even spacing on the left and right */
  flex-shrink: 0;
}

.scroll-slide img {
  height: 100%;
  width: auto; /* ⬅️ This forces the width to automatically scale with the height */
  object-fit: contain; /* ⬅️ Guarantees 0% cropping of your artwork */
  border-radius: 6px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
}

/* Infinite loop animation for variable widths */
@keyframes dynamic-scroll {
  0% {
    transform: translateX(0);
  }
  100% {
    /* Moves left by exactly one-third of the total track length */
    transform: translateX(-33.3333%); 
  }
}

/* Pause on hover */
.scroll-gallery-container:hover .scroll-gallery-track {
  animation-play-state: paused;
}
</style>