---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<html>
  <head>
    <link href="./mystyle.css" rel="stylesheet" type="text/css"/>
    <style>
      .slideshow-container {
        max-width: 1000px;
        position: relative;
        margin: auto;
        overflow: hidden;
      }
      
      .mySlides {
        display: none;
      }
    </style>
  </head>
  <body>
    <div class="slideshow-container">
      <div class="mySlides">
        <img src="/images/image1.jpg" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/image2.jpg" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/image3.jpg" style="width:100%">
      </div>
    </div>
    <script>
      var slideIndex = 0;
      showSlides();
      
      function showSlides() {
        var i;
        var slides = document.getElementsByClassName("mySlides");
        for (i = 0; i < slides.length; i++) {
          slides[i].style.display = "none";
        }
        slideIndex++;
        if (slideIndex > slides.length) {slideIndex = 1}
        slides[slideIndex-1].style.display = "block";
        setTimeout(showSlides, 2000); // Change image every 2 seconds
      }
    </script>
  </body>
</html>

