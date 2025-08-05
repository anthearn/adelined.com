---
layout: default
---

<div class="grid">
  <div class="quad quad1">
    <div class="logo-container">
      <img src="{{ '/assets/images/adelined_A1_notext.png' | relative_url }}" alt="Adelined logo" class="logo">
      <div class="brand-text">Adelined</div>
    </div>
  </div>

  <div class="quad quad2">
    <video id="heroVideo" autoplay muted loop playsinline class="hero-video">
      <source src="{{ '/assets/videos/morning_purple_coffee.mp4' | relative_url }}" type="video/mp4">
    </video>
  </div>

  <div class="quad quad3">
    <div class="text-block">Smart Sponsorships for Brands & Podcasters</div>
  </div>

  <div class="quad quad4">
    <div class="text-block">How it works →</div>
  </div>
</div>

<script>
  window.addEventListener("DOMContentLoaded", () => {
    const video = document.getElementById("heroVideo");
    if (video) {
      video.playbackRate = 0.3;
    }
  });
</script>