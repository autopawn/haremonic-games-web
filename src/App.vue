<script setup>
import CopyrightNotice from './components/CopyrightNotice.vue'
import BannerSection from './components/BannerSection.vue'
import PortfolioSection from './components/PortfolioSection.vue'
</script>

<template>
<div id="page-wrapper">

<!-- Header -->
  <section id="header">
    <!-- Logo -->
    <h1><a href="index.html">Haremonic Games</a></h1>
    <BannerSection/>
  </section>

<!-- Main -->
  <section id="main">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <PortfolioSection/>
        </div>
      </div>
    </div>
  </section>

<!-- Footer -->
  <section id="footer">
    <div class="container">
      <div class="row">
        <div class="col-4 col-6-medium col-12-small">
          <section id="subscription">
            <h3>Subscribe to get notified of new releases</h3>
            <form action="https://form2channel.com/?apikey=0gfB2YqtVNLdkoiHSAe5Wi5yxPdSrN" method="POST">
              <input name="formto_redirect" type="hidden" value="https://haremonic.games"/>
              <textarea name="formto_honey" style="display: inline; width: 0px; height: 0px; border: 0; padding: 0; margin: 0"/>
                <input type="email" name="EmailField" placeholder="your@email.com"/>
                <button type="Submit">Sign Up</button>
            </form>
          </section>
        </div>
        <div class="col-4 col-6-medium col-12-small">
          <section>
            <ul class="divided">
              <li><a href="#banner">About Us</a></li>
              <li><a href="#hare0">Hare 136: Slider</a></li>
            </ul>
          </section>
        </div>
        <div class="col-4 col-12-medium">
          <section>
            <ul class="social">
              <li><a class="icon brands fa-twitter" href="https://twitter.com/HaremonicGames"><span class="label">Twitter</span></a></li>
              <li><a class="icon brands fa-itch-io" href="https://haremonic-games.itch.io"><span class="label">Itch.io</span></a></li>
              <li><a class="icon brands fa-google-play" href="https://play.google.com/store/apps/dev?id=7051079967543291026"><span class="label">Google Play</span></a></li>
            </ul>
            <ul class="contact">
              <li>
                <address>
                <h3>Mail</h3>
                <p><a href="mailto:contact@haremonic.games">contact@haremonic.games</a></p>
              </address>
              </li>
            </ul>
          </section>
        </div>
        <div class="col-12"> 
            <CopyrightNotice/>
        </div>
      </div>
    </div>
  </section>
</div>
</template>
