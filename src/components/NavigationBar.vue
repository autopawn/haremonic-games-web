<template>
  <!-- Nav -->
  <nav id="nav">
    <ul>
      <li class="current"><a href="index.html">Home</a></li>
      <li>
        <a href="#">Dropdown</a>
        <ul>
          <li><a href="#">Lorem ipsum dolor</a></li>
          <li><a href="#">Magna phasellus</a></li>
          <li><a href="#">Etiam dolore nisl</a></li>
          <li>
            <a href="#">Phasellus consequat</a>
            <ul>
              <li><a href="#">Magna phasellus</a></li>
              <li><a href="#">Etiam dolore nisl</a></li>
              <li><a href="#">Veroeros feugiat</a></li>
              <li><a href="#">Nisl sed aliquam</a></li>
              <li><a href="#">Dolore adipiscing</a></li>
            </ul>
          </li>
          <li><a href="#">Veroeros feugiat</a></li>
        </ul>
      </li>
      <li><a href="left-sidebar.html">Left Sidebar</a></li>
      <li><a href="right-sidebar.html">Right Sidebar</a></li>
      <li><a href="no-sidebar.html">No Sidebar</a></li>
    </ul>
  </nav>
</template>

<style scoped>
#nav {
  margin: 2.5em 0 0 0;
}

#nav > ul {
  margin: 0;
}

#nav > ul > li {
  display: inline-block;
  font-style: italic;
  margin: 0 0.35em 0 0.35em;
}

#nav > ul > li > ul {
  display: none;
}

#nav > ul > li > a {
  border-radius: 5px;
  color: #5d5d5d;
  text-decoration: none;
  padding: 0.6em 1.2em 0.6em 1.2em;
  -moz-transition: background-color .25s ease-in-out;
  -webkit-transition: background-color .25s ease-in-out;
  -ms-transition: background-color .25s ease-in-out;
  transition: background-color .25s ease-in-out;
  outline: 0;
}

#nav > ul > li:hover > a, #nav > ul > li.active > a {
  background: #f3f3f3;
}

#nav > ul > li.current > a {
  background: #d52349;
  color: #fff !important;
  font-weight: 700;
}

.dropotron {
  border-radius: 5px;
  background-color: #252122;
  background-color: rgba(34, 30, 31, 0.98);
  padding: 1.25em 1.5em 1.25em 1.5em;
  font-style: italic;
  min-width: 13em;
  box-shadow: 0px 8px 15px 0px rgba(0, 0, 0, 0.5);
  text-align: left;
  margin-top: -1.25em;
  margin-left: -1px;
  list-style: none;
}

.dropotron a, .dropotron span {
  color: #aaa;
  text-decoration: none;
  -moz-transition: color .25s ease-in-out;
  -webkit-transition: color .25s ease-in-out;
  -ms-transition: color .25s ease-in-out;
  transition: color .25s ease-in-out;
}

.dropotron li {
  padding: 0.25em 0 0.25em 0;
}

  .dropotron li:hover > a, .dropotron li:hover > span {
    color: #fff;
  }

.dropotron.level-0 {
  margin-top: 2em;
}

.dropotron.level-0:before {
  content: '';
  display: block;
  position: absolute;
  left: 50%;
  margin-left: -10px;
  top: -9px;
  border-left: solid 10px transparent;
  border-right: solid 10px transparent;
  border-bottom: solid 10px #252122;
  border-bottom-color: rgba(34, 30, 31, 0.98);
}

/* Medium */
@media screen and (max-width: 980px) {
  #nav {
    display: none;
  }
  
  #page-wrapper {
    -moz-backface-visibility: hidden;
    -webkit-backface-visibility: hidden;
    -ms-backface-visibility: hidden;
    backface-visibility: hidden;
    -moz-transition: -moz-transform 0.5s ease;
    -webkit-transition: -webkit-transform 0.5s ease;
    -ms-transition: -ms-transform 0.5s ease;
    transition: transform 0.5s ease;
    padding-bottom: 1px;
  }

  #titleBar {
    -moz-backface-visibility: hidden;
    -webkit-backface-visibility: hidden;
    -ms-backface-visibility: hidden;
    backface-visibility: hidden;
    -moz-transition: -moz-transform 0.5s ease;
    -webkit-transition: -webkit-transform 0.5s ease;
    -ms-transition: -ms-transform 0.5s ease;
    transition: transform 0.5s ease;
    display: block;
    height: 44px;
    left: 0;
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 10001;
    background: none;
  }

  #titleBar .toggle {
    text-decoration: none;
    width: 80px;
    height: 60px;
  }

  #titleBar .toggle:before {
    -moz-osx-font-smoothing: grayscale;
    -webkit-font-smoothing: antialiased;
    display: inline-block;
    font-style: normal;
    font-variant: normal;
    text-rendering: auto;
    line-height: 1;
    text-transform: none !important;
    font-family: 'Font Awesome 5 Free';
    font-weight: 900;
  }

  #titleBar .toggle:before {
    content: '\f0c9';
    display: block;
    position: absolute;
    left: 10px;
    top: 10px;
    width: 50px;
    height: 40px;
    line-height: 40px;
    font-size: 18px;
    color: #fff;
    text-align: center;
    background: rgba(150, 150, 150, 0.75);
    border-radius: 5px;
  }

  #titleBar .toggle:active:before {
    background-color: #969696;
  }

  #navPanel {
    -moz-backface-visibility: hidden;
    -webkit-backface-visibility: hidden;
    -ms-backface-visibility: hidden;
    backface-visibility: hidden;
    -moz-transform: translateX(-275px);
    -webkit-transform: translateX(-275px);
    -ms-transform: translateX(-275px);
    transform: translateX(-275px);
    -moz-transition: -moz-transform 0.5s ease;
    -webkit-transition: -webkit-transform 0.5s ease;
    -ms-transition: -ms-transform 0.5s ease;
    transition: transform 0.5s ease;
    display: block;
    height: 100%;
    left: 0;
    overflow-y: auto;
    position: fixed;
    top: 0;
    width: 275px;
    z-index: 10002;
    color: #858484;
    background-image: url("images/bg.png");
    box-shadow: inset -3px 0px 5px 0px rgba(0, 0, 0, 0.35);
  }

  #navPanel .link {
    display: block;
    color: #888;
    text-decoration: none;
    height: 44px;
    line-height: 44px;
    border-top: solid 1px rgba(255, 255, 255, 0.05);
    padding: 0 1em 0 1em;
    font-style: italic;
  }

  #navPanel .link:first-child {
    border-top: 0;
  }

  #navPanel .indent-1 {
    display: inline-block;
    width: 1em;
  }

  #navPanel .indent-2 {
    display: inline-block;
    width: 2em;
  }

  #navPanel .indent-3 {
    display: inline-block;
    width: 3em;
  }

  #navPanel .indent-4 {
    display: inline-block;
    width: 4em;
  }

  #navPanel .indent-5 {
    display: inline-block;
    width: 5em;
  }

  #navPanel .depth-0 {
    color: #fff;
  }

  body.navPanel-visible #page-wrapper {
    -moz-transform: translateX(275px);
    -webkit-transform: translateX(275px);
    -ms-transform: translateX(275px);
    transform: translateX(275px);
  }

  body.navPanel-visible #titleBar {
    -moz-transform: translateX(275px);
    -webkit-transform: translateX(275px);
    -ms-transform: translateX(275px);
    transform: translateX(275px);
  }

  body.navPanel-visible #navPanel {
    -moz-transform: translateX(0);
    -webkit-transform: translateX(0);
    -ms-transform: translateX(0);
    transform: translateX(0);
  }
}
</style>