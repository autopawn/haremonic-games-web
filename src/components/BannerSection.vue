<template>
<!-- Banner -->
<section id="banner">
  <header>
    <h2>Hello there!🎵🐇</h2>
    <p>We are a small team of programmers and musicians, and together we are making cute games</p>
  </header>
</section>
</template>

<style scoped>
#banner {
  background: #FFFFFF url("@/assets/images/banner.png");
  background-position: center center;
  background-size: cover;
  background-repeat: no-repeat;
  text-align: center;
  position: relative;
  padding: 8em 0;
  margin: 4em 0 0 0;
}

#banner header {
  background-color: rgba(48, 48, 48, 0.75);
  display: inline-block;
  padding: 2.5em 5em;
  border-radius: 5px;
}

#banner header h2 {
  color: #fff;
  font-weight: 700;
  font-size: 2.5em;
  margin: 0 0 0.65em 0;
}

#banner header p {
  color: #d5d5d5;
  padding: 0;
  font-style: normal;
  margin: 0;
  font-size: 1.5em;
}

/* Small */
@media screen and (max-width: 736px) {
  #banner {
    padding: 6em 0;
    margin: 2em 0 0 0;
  }

  #banner header {
    padding: 1.5em 1em 1.5em 1em;
    display: block;
    border-radius: 0;
  }

  #banner header h2 {
    font-size: 1.5em;
    line-height: 1.5em;
    margin: 0 0 0.25em 0;
  }

  #banner header p {
    font-size: 1.2em;
  }
}

/* Large */
@media screen and (max-width: 1280px) {
  #banner {
    padding: 6em 0;
    margin: 3em 0 0 0;
  }
}
</style>