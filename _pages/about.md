---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<style>
    .area_pics img{
        width:380px;
        margin-left:50px
        float:left;
    }
  
        .slideshow-container {
        max-width: 1000px;
        position: relative;
        margin: auto;
        overflow: hidden;
      }
      
      .mySlides {
        display: none;
      }
      
      .prev, .next {
        cursor: pointer;
        position: absolute;
        top: 50%;
        width: auto;
        margin-top: -22px;
        padding: 16px;
        color: white;
        font-weight: bold;
        font-size: 18px;
        transition: 0.6s ease;
        border-radius: 0 3px 3px 0;
        user-select: none;
      }
      
      .next {
        right: 0;
        border-radius: 3px 0 0 3px;
      }
      
      .prev:hover, .next:hover {
        background-color: rgba(0,0,0,0.8);
      }
  
      #news {
      
      height: 100px;
       overflow-y: scroll;
    }
</style>
<body align="justify">
<div class="area_pics">
 <img src="/images/research1.png" />
 <img src="/images/research2.png" />
</div>
<div class="area_pics">
 <img src="/images/research3.png" />
 <img src="/images/research4.jpg" />
</div>
<div>
    <p> News about the laboratory</p>
<div class="news">

<li>Welcome our new research assistant Zeyu Xi! -- 2022.06.13</li>
<li>Welcome our new research assistant Jingwen Zhang!--2022.06.08</li>
<li>DMO PSF paper is out at Optics Letters! Congratulations Shuang Fu!--2022.06.08</li>
<li> globLoc paper is out at Nature Communications! Congratulations Wei Shi!--2022.06.06</li>
  </div>
   </div>     


  <div class="slideshow-container">
      <div class="mySlides">
        <img src="/images/image4.jpg" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/image5.jpg" style="width:100%">
      </div>
      <div class="mySlides">
        <img src="/images/image6.jpg" style="width:100%">
      </div>
      <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
      <a class="next" onclick="plusSlides(1)">&#10095;</a>
    </div>
    <script>
      var slideIndex = 1;
      showSlides(slideIndex);
      
      function plusSlides(n) {
        showSlides(slideIndex += n);
      }
      
      function showSlides(n) {
        var i;
        var slides = document.getElementsByClassName("mySlides");
        if (n > slides.length) {slideIndex = 1}
        if (n < 1) {slideIndex = slides.length}
        for (i = 0; i < slides.length; i++) {
            slides[i].style.display = "none";
        }
        slides[slideIndex-1].style.display = "block";
      }
    </script>
  

</body>
  
