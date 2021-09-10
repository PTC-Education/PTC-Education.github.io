---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
permalink: /
---

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: 30px 30px 0px 30px;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: black;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: white;
  text-shadow: 0 0 20px black;
  font-size: 35px;
  padding: 8px 12px;
  position: absolute;
  width: 100%;
  bottom: 8px;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
</style>
</head>

<section class="section">
    <div class="container">
        <h1 class="title header-home">Digital Transformation in Education</h1>
        <a href="https://www.ptc.com/en/industry-insights/digital-transformation">Digital Transformation</a> is a strategy being used by industry to solve problems with smart, connected technologies. PTC Education works to bring these industry ready technologies to researchers and teachers around the world. We hope this site helps to enable you to get started on your digital transformation journey.

<div class="slideshow-container">

<div class="mySlides fade">
  <a href="/docs/solutions/onshapedx"><div class="numbertext">1 / 3</div>
  <img src="resources/UR3OnshapeDigitalTwin.gif" style="width:100%">
  <div class="text">Onshape Digital Twins</div></a>
</div>

<div class="mySlides fade">
  <a href="/docs/thought-leadership"><div class="numbertext">2 / 3</div>
  <img src="resources/ThoughtLeadershipBYU.gif" style="width:100%">
  <div class="text">Thought Leadership</div></a>
</div>

<div class="mySlides fade">
  <a href="/blog"><div class="numbertext">3 / 3</div>
  <img src="resources/BlogTufts.gif" style="width:100%">
  <div class="text">Blog</div></a>
</div>

<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
</div>

<script>
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function next(n) {
    showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>
<div class="container" margin="300px 0px 100px 0px">
<p margin="300px 0px 100px 0px">Below is a framework for understanding how PTC technologies work together to enable DX Engineers to solve problems with digitally connected technologies. We believe that the core disciplinary work of a digital tranformation engineer is in connectivity - connecting physical machines to the cloud through IoT, connecting digital assets throughout the digital thread, and connecting digital information back to the physical world through augmented reality. In addition to being able to use all of the techonlogies within the connectivity categoery, DX engineers must have a strong foundation in CAD and CAE technologies, as well as PLM and data management and analysis technologies.</p>
</div>
        <div class="container">
            <p style="text-align:center"><img src="../resources/Adv-Tech-Map-basic.jpg" width="100%" alt="DX Technologies Map" margin="300px 0px 100px 0px"/></p>
        </div>
    </div>
    <div class="container">
        <div>Click on an item below to get started with PTC technologies, learn about various integrations, or see how thought leaders are bringing digital transformation to education.
        </div>
    </div>
    <div class="container">
        <div class="columns is-vcentered is-centered is-multiline ">
            <div class="column is-one-third is-vcentered is-centered">
                <a href="/docs/tech"><p>
                <img src="resources/IoT-icon.png" alt=""/></p>
                <div class="subtitle" style="text-align:center">Technologies</div>
                </a>
            </div>
            <div class="column is-one-third">
                <a href="/docs/solutions"><p><img src="resources/Integrations-icon.png" alt=""/></p>
                <div class="subtitle" style="text-align:center">Solutions</div>
                </a>
            </div>
            <div class="column is-one-third">
                <a href="/docs/thought-leadership">
                <p><img src="resources/Academic-icon.png" alt=""/></p>
                <div class="subtitle" style="text-align:center">Thought Leadership</div>
                </a>
            </div>
        </div>
    </div>
</section>
<section class="section">
    <div class="container">
        <h1 class="title header-home">What is PTC Education?</h1>
        <div class="column is-full" style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%;">
            <iframe src="https://www.youtube.com/embed/YTG9KiD3n7k" frameborder="0" allow="autoplay;"
                    allowfullscreen class="video"
                    style="position: absolute;top: 0; left: 0; width: 100%; height: 100%;">
                <img src="resources/toolboxVideoPlaceholder.jpg" style="border: 0px">
            </iframe>
        </div>
    </div>
</section>