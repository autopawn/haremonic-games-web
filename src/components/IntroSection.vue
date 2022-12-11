<template>
<!-- Intro -->
<section id="intro" class="container">
  <div class="row">
    <div class="col-4 col-12-medium">
      <section class="first">
        <i class="icon solid featured fa-cog"></i>
        <header>
          <h2>Ipsum consequat</h2>
        </header>
        <p>Nisl amet dolor sit ipsum veroeros sed blandit consequat veroeros et magna tempus.</p>
      </section>
    </div>
    <div class="col-4 col-12-medium">
      <section class="middle">
        <i class="icon solid featured alt fa-bolt"></i>
        <header>
          <h2>Magna etiam dolor</h2>
        </header>
        <p>Nisl amet dolor sit ipsum veroeros sed blandit consequat veroeros et magna tempus.</p>
      </section>
    </div>
    <div class="col-4 col-12-medium">
      <section class="last">
        <i class="icon solid featured alt2 fa-star"></i>
        <header>
          <h2>Tempus adipiscing</h2>
        </header>
        <p>Nisl amet dolor sit ipsum veroeros sed blandit consequat veroeros et magna tempus.</p>
      </section>
    </div>
  </div>
  <footer>
    <ul class="actions">
      <li><a href="#" class="button large">Get Started</a></li>
      <li><a href="#" class="button alt large">Learn More</a></li>
    </ul>
  </footer>
</section>
</template>

<style scoped>
#intro {
  text-align: center;
  overflow: hidden;
}

#intro section {
  margin: 3em 0;
  padding: 2.5em 0;
}

#intro h2 {
  font-size: 1.75em;
}

#intro p {
  margin: 0;
}

#intro .middle {
  position: relative;
  z-index: 1;
}

#intro .middle:before {
  content: '';
  width: 32px;
  height: 100%;
  position: absolute;
  left: -24px;
  top: 0;
  display: block;
  z-index: -1;
  box-shadow: 32px 0 0 0 #fff, 0 -32px 0 0 #fff, 0 32px 0 0 #fff, 32px 32px 0 0 #fff, 32px -32px 0 0 #fff, 0 0 32px 0 rgba(0, 0, 0, 0.15);
}

#intro .middle:after {
  content: '';
  width: 32px;
  height: 100%;
  position: absolute;
  right: -24px;
  top: 0;
  display: block;
  z-index: -1;
  box-shadow: -32px 0 0 0 #fff, 0 -32px 0 0 #fff, 0 32px 0 0 #fff, -32px 32px 0 0 #fff, -32px -32px 0 0 #fff, 0 0 32px 0 rgba(0, 0, 0, 0.15);
}

#intro .button {
  min-width: 12em;
}

#intro footer {
  margin: 0;
}

/* Large */
@media screen and (max-width: 1280px) {
  #intro {
    padding: 0;
  }
  #intro section {
    padding: 1em 2em;
  }
  #intro .middle:before {
    left: -12px;
  }
  #intro .middle:after {
    right: -12px;
  }
}

/* Medium */
@media screen and (max-width: 980px) {
  #intro {
    padding: 3em 0 0 0;
  }
  #intro section {
    position: relative;
    border-top: solid 1px #dfdfdf;
    margin: 0;
    padding: 40px 0 0 0;
  }
  #intro section.first {
    border-top: 0;
    padding-top: 0;
  }
  #intro section p {
    margin: 0;
  }
  #intro .middle:before, #intro .middle:after {
    display: none;
  }
  #intro footer {
    padding: 3em 0 0 0;
  }
  #intro footer ul.actions {
    margin-bottom: 0;
  }
}

/* Small */
@media screen and (max-width: 736px) {
  #intro {
    padding: 2em 0 0 0;
  }

  #intro section {
    padding: 40px 0 0 0;
    margin: 20px 0 0 0;
  }

  #intro h2 {
    font-size: 1.25em;
  }
}
</style>