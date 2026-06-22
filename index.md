---
layout: null
title: The Morning After
---


<link rel="stylesheet" href="{{ site.baseurl }}/assets/css/main.css">

<div class="hero" style="background-image: url('assets/img/LibraryHero.png');">
  <div class="hero-overlay">
    <!--<h1>The Morning After</h1>-->
        <div class="parallax-title">
            <img src="assets/img/SteamLogo.png" alt="The Morning After" class="game-title-logo">
        </div>
    <h2>A makeout mystery you'll be thirsting to solve!</h2>
    <a class="btn" href="#trailer">Watch Trailer</a>
  </div>
</div>

<section class="section">

  <div class="feature">
    <img src="assets/img/bg.png">
    <div>
      <h2>Reality Deformation</h2>
      <p>Environments shift as memory collapses. No two paths are identical.</p>
    </div>
  </div>

  <div class="feature reverse">
    <img src="assets/img/bg.png">
    <div>
      <h2>Fragmented Exploration</h2>
      <p>Navigate layered spaces built from corrupted recollections.</p>
    </div>
  </div>

  <div class="feature">
    <img src="assets/img/bg.png">
    <div>
      <h2>Signal-Based Storytelling</h2>
      <p>Discover narrative through visual echoes and environmental traces.</p>
    </div>
  </div>

</section>

<section class="full-banner" style="background-image: url('assets/img/bg.png');">
  <div class="banner-text">
    <h2>Every frame hides a clue.</h2>
  </div>
</section>

<section class="section" id="trailer">

  <h2>Gameplay</h2>

  <div class="video-wrapper">
    <iframe 
      src="https://www.youtube.com/embed/VIDEO_ID"
      frameborder="0"
      allowfullscreen>
    </iframe>
  </div>

</section>

<section class="cta">
  <h2>Enter the Depths</h2>
  <a class="btn" href="#">Download Demo</a>
</section>

<script>
window.addEventListener("scroll", () => {
  const logo = document.querySelector(".game-title-logo");
  const scrollY = window.scrollY;

  // slower movement = more depth
  const offset = scrollY * 0.25;

  logo.style.transform = `translateY(${offset}px)`;
});
</script>