<template>
<!-- Portfolio -->
<section>
  <header class="major">
    <h2>Our Projects</h2>
  </header>
  
  <article id="slider" class="slider portfolio-item">
  <div class="container portfolio-item">
      <div class="poster">
        <img src="@/assets/images/slider/poster.png" class="poster d-block mx-auto text-center" alt="...">
      </div>
      <div class="portfolio-item main">
        <header class="portfolio-item">
          <h2>Hare 136 - Slider</h2>
          <p>
            <b>Hare 136 - Slider</b> is a simple and relaxing but increasingly challenging sliding puzzle game, in which you help cute bunnies get to their home sliding through the world.
          </p>
        </header>
        <footer class="portfolio-item">
          <h5>Play on</h5> 
          <a href="https://play.google.com/store/apps/details?id=games.haremonic.slider" class="store-btn">
            <img alt="Get it on Google Play" src="@/assets/images/badges/google-play-badge.png" class="store-btn"/>
          </a>
          <a href="https://haremonic-games.itch.io/hare136-slider" class="store-btn">
            <img alt="Available on itch.io" src="@/assets/images/badges/itch-io-badge.svg" class="store-btn"/>
          </a>
        </footer>
      </div>
    </div>
</article>


</section>
</template>


<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Lato");
@import url('https://fonts.googleapis.com/css2?family=Merriweather');

body {
  margin: 0;
	padding: 0;
  border: 0;
  vertical-align: baseline;
}

section#banner {
  background-image: url('@/assets/images/banner.png');
  background-position: center top;
  background-size: cover;
  background-repeat: no-repeat;
  position: fixed;
  top: 0;
  width: 100%;
  min-height: 405px;
  padding: 8em 0;
}


article#slider {
  background-image: url('@/assets/images/slider/bg.png');
}

article.portfolio-item {
  background-size: cover;
  padding: 4em;
}

header.portfolio-item {
  padding-top: 1em;
}

.portfolio-item.container {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
}

.portfolio-item.main {
  flex: 1 1 300px;
} 

div.poster {
  float: left;
  max-width: 300px;
  margin-right: 40px;
}

img.poster {
  width: 100%;
}

img.store-btn {
  height: 50px;
  padding: 10px;
}

p {
  font-family: Lato;
  font-weight: normal;
}

h1,h2,h3,h4,h5,h6 {
  font-family: Merriweather;
  font-weight: bolder;
}
</style>
