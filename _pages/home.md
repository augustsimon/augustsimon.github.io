---
title: "home"
permalink: /home/
layout: single
classes: wide
author_profile: true
---

welcome! this is my repository for music, art, and other stuff that i want to keep track of. you can navigate thru categories using the links above ^. each one has different collections to explore.

<!-- gallery scroll box -->
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
</style>