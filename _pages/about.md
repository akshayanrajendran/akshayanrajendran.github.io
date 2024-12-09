---
permalink: /
title: "Hello there, I'm Akshayan!👋"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

👨‍💻 I'm a Computer Engineering Freshman at Toronto Metropolitan University, Canada

🚀 I love aerospace, aviation, and computer technology and aspire to do research in these sectors in the future.

🎵 I am also a Indian classical carnatic percussionist and a national level quizzer.

⚙️ As a creative and determined individual, I like to explore and learn more in the domain of science and technology.

<div id="slideshow">
    <img src=/images/akshayanspic1.jpg alt="Image 1">
    <img src="http://placehold.it/300x200&text=foo2.jpg" alt="Image 2" style="display: none;">
    <img src="http://placehold.it/300x200&text=foo3.jpg" alt="Image 3" style="display: none;">
    <img src="http://placehold.it/300x200&text=foo4.jpg" alt="Image 4" style="display: none;">
    <img src="http://placehold.it/300x200&text=foo5.jpg" alt="Image 5" style="display: none;">
</div>

<script>
    var slideshow = document.getElementById('slideshow');
    var slides = slideshow.getElementsByTagName('img');
    var idx = 0;

    function changeSlide() {
        slides[idx].style.display = 'none'; // Hide current slide
        idx = (idx + 1) % slides.length; // Move to the next slide
        slides[idx].style.display = 'block'; // Show next slide
    }

    setInterval(changeSlide, 3000); // Change slide every 3 seconds
</script>

![akshayanspic1](/images/akshayanspic1.jpg){:align-bottom width="300px"}

![akshayanspic2](/images/akshayanspic2.jpg)
{:align-right width="10px"}
