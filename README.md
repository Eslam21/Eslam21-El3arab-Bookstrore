# Eslam21-El3arab-Bookstrore.github.io

<!DOCTYPE html>
<html>
<head>

<style>
body {
  background-image: url("https://i.pinimg.com/564x/02/aa/9e/02aa9e355db242bbad8085bc517152d2.jpg");
}
</style>

<!-- logo -->

<p><a href="https://www.facebook.com/al3arrab4books">
<img src="3arrab.png"style="width:100%;height:220px;object-fit:fill;">

<!-- bar -->
<style>
ul {
  list-style-type: none;
  margin: 0 ;
  padding: 0;
  overflow: hidden;
  background-color: black;
}

li {
  float: left;
}

li a, .dropbtn {
  display: inline-block;
  color: white;
  text-align: center;
  padding: 25px 120px;
  text-decoration: none;
}

li a:hover, .dropdown:hover .dropbtn {
  background-color: red;
}

li.dropdown {
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content a:hover {background-color: #f1f1f1;}

.dropdown:hover .dropdown-content {
  display: block;
}
</style>





<!-- slideshow -->

<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  top:100px ;
  left: 0px ;
  margin: 0;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
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
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
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

<!-- slideshow -->



</head>
<body>

</a></p>


<!--navbar  -->
<ul>
  <li><<a href="#home" style="font-size: 35px;" >Home</a></li>
  <li class="dropdown">
    <a href="javascript:void(0)" class="dropbtn" style="font-size: 25px">Books</a>
    <div class="dropdown-content">
      <a href="Horror.html">Horror</a>
      <a href="computer science.html">Computer Science</a>
      <a href="Comics.html">Graphic Novels</a>
       <a href="History.html">History</a>
        <a href="biography.html">Biography</a>
        <a href="Sci-fi.html">Science Fiction</a>
         <a href="Movies Books.html">Movies Books</a>
    </div>
    <li><a href="articels.html" style="font-size: 25px">Articles</a></li>
    <li><a href="about us.html" style="font-size: 25px">About Us</a></li>
  </li>
</ul>

<h1 style="background-color:yellow;position: relative;top: 100px  ">Why should we read books ?</h1>
<iframe src="https://www.youtube.com/embed/6Gw5dK48MtI" style="position:relative; top: 100px; left:0;width:700px ;height:500px" ></iframe>
<br>
<br>
<br>
<h1 style="background-color:yellow;position: relative;top: 100px  ">Best selling Books</h1>

<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 3</div>
  <img src="book1.jpg" style="width:100%">
  <div class="text">Caption Text</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src="book2.jpg" style="width:100%">
  <div class="text">Caption Two</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src="book3.jpg" style="width:100%">
  <div class="text">Caption Three</div>
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


<style>
body {
  background-image: url("https://i.pinimg.com/564x/02/aa/9e/02aa9e355db242bbad8085bc517152d2.jpg");
}
</style>
</body>
</html>
