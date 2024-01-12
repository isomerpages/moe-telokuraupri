---
title: Gallery
permalink: /tkps-gallery/
variant: markdown
description: ""
---



<style>
body {
  font-family: Arial;
  margin: 0;
}

* {
  box-sizing: border-box;
}

img {
  vertical-align: middle;
}

/* Position the image container (needed to position the left and right arrows) */
.container {
  position: relative;
}

/* Hide the images by default */
.mySlides {
  display: none;
}

/* Add a pointer when hovering over the thumbnail images */
.cursor {
  cursor: pointer;
}

/* Next & previous buttons */
.prev,
.next {
  cursor: pointer;
  position: absolute;
  top: 40%;
  width: auto;
  padding: 16px;
  margin-top: -50px;
  color: white;
  font-weight: bold;
  font-size: 20px;
  border-radius: 0 3px 3px 0;
  user-select: none;
  -webkit-user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover,
.next:hover {
  background-color: rgba(0, 0, 0, 0.8);
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* Container for image text */
.caption-container {
  text-align: center;
  background-color: #222;
  padding: 2px 16px;
  color: white;
}

.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Six columns side by side */
.column {
  float: left;
  width: 16.66%;
}

/* Add a transparency effect for thumnbail images */
.demo {
  opacity: 0.6;
}

.active,
.demo:hover {
  opacity: 1;
}
</style>


<h2 style="text-align:center">Slideshow Gallery</h2>

<div class="container">
  <div class="mySlides">
    <div class="numbertext">1 / 6</div>
    <img style="width:100%" src="img_woods_wide.jpg">
  </div>

  <div class="mySlides">
    <div class="numbertext">2 / 6</div>
    <img style="width:100%" src="img_5terre_wide.jpg">
  </div>

  <div class="mySlides">
    <div class="numbertext">3 / 6</div>
    <img style="width:100%" src="img_mountains_wide.jpg">
  </div>
    
  <div class="mySlides">
    <div class="numbertext">4 / 6</div>
    <img style="width:100%" src="img_lights_wide.jpg">
  </div>

  <div class="mySlides">
    <div class="numbertext">5 / 6</div>
    <img style="width:100%" src="img_nature_wide.jpg">
  </div>
    
  <div class="mySlides">
    <div class="numbertext">6 / 6</div>
    <img style="width:100%" src="img_snow_wide.jpg">
  </div>
    
  <a class="prev">❮</a>
  <a class="next">❯</a>

  <div class="caption-container">
    <p id="caption"></p>
  </div>

  <div class="row">
    <div class="column">
      <img alt="The Woods" style="width:100%" src="img_woods.jpg" class="demo cursor">
    </div>
    <div class="column">
      <img alt="Cinque Terre" style="width:100%" src="img_5terre.jpg" class="demo cursor">
    </div>
    <div class="column">
      <img alt="Mountains and fjords" style="width:100%" src="img_mountains.jpg" class="demo cursor">
    </div>
    <div class="column">
      <img alt="Northern Lights" style="width:100%" src="img_lights.jpg" class="demo cursor">
    </div>
    <div class="column">
      <img alt="Nature and sunrise" style="width:100%" src="img_nature.jpg" class="demo cursor">
    </div>    
    <div class="column">
      <img alt="Snowy Mountains" style="width:100%" src="img_snow.jpg" class="demo cursor">
    </div>
  </div>
</div>


    


