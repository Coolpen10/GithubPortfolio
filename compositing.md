<nav class="custom-nav">
  <a href="./" class="nav-link">Home</a>
  <a href="motion-graphics.html" class="nav-link">Motion Graphics</a>
  <a href="compositing.html" class="nav-link">2D Compositing</a>
  <a href="programming.html" class="nav-link">Unity Programming</a>
</nav>
<hr>


  <div class="carousel-container">

  <div class="carousel-slide active-slide">
    <div class="featured-container">
      <div class="featured-text">
        <h2>Do No Harm (The Opioid Trilogy | PBS)</h2>
        <p>The story of Raina, who spent 17 years battling heroin addiction before finding her healing path through alternative approaches.</p>
        <p><strong>Role:</strong> Lead Compositor.</p>
        <p><strong>Software:</strong> After Effects</p>
      </div>
      <div class="featured-video">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/8qQw2yy9p20?si=eg8-K_5_1XqCufUp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
      </div>
    </div>
  </div>

  <div class="carousel-slide">
    <div class="featured-container">
      <div class="featured-text">
        <h2>Coming Home (The Opioid Trilogy | PBS)</h2>
        <p>Compositing together line work and textures to tell the story of a recovering addict who aims to help others find their way.</p>
        <p><strong>Role:</strong> Lead Compositor.</p>
        <p><strong>Software:</strong> After Effects</p>
      </div>
      <div class="featured-video">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/JZYJ_1wpqNQ?si=KFd-bjF4DCCSqyg0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
      </div>
    </div>
  </div>

  <div class="carousel-slide">
    <div class="featured-container">
      <div class="featured-text">
        <h2>Addiction Animated (The Opioid Trilogy | PBS)</h2>
        <p>The first entry in The Opioid Trilogy, highlighting phone calls between the filmmaker and her brother as he battles against his addiction.</p>
        <p><strong>Role:</strong> Lead Compositor.</p>
        <p><strong>Software:</strong> After Effects</p>
      </div>
      <div class="featured-video">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/LBC7FfG1hc0?si=VmHgtdKjbmFOx1ZI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
      </div>
    </div>
  </div>

  <a class="prev" onclick="changeSlide(-1)">&#10094;</a>
  <a class="next" onclick="changeSlide(1)">&#10095;</a>

</div>
<hr>



## 2D compositing work

<div class="motion-grid">

  <div class="motion-item">
    <img src="compClip_01.gif" alt="Description of Project 1">
  </div>

  <div class="motion-item">
    <img src="compClip_02.gif" alt="Description of Project 1">
  </div>

  <div class="motion-item">
    <img src="compClip_03.gif" alt="Description of Project 1">
  </div>

  <div class="motion-item">
    <img src="compClip_04.gif" alt="Description of Project 1">
  </div>

  <div class="motion-item">
    <img src="compClip_05.gif" alt="Description of Project 1">
  </div>

  <div class="motion-item">
    <img src="compClip_06.gif" alt="Description of Project 1">
  </div>

  <div class="motion-item">
    <img src="compClip_07.gif" alt="Description of Project 1">
  </div>

  <div class="motion-item">
    <img src="compClip_08.gif" alt="Description of Project 1">
  </div>

  <div class="motion-item">
    <img src="compClip_09.gif" alt="Description of Project 1">
  </div>

</div>

## Javascript
<script>
let slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function changeSlide(n) {
  showSlides(slideIndex += n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("carousel-slide");
  
  // If we go past the last slide, loop back to the first
  if (n > slides.length) {slideIndex = 1}
  
  // If we go before the first slide, loop to the last
  if (n < 1) {slideIndex = slides.length}
  
  // Hide all slides first
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
    slides[i].className = slides[i].className.replace(" active-slide", "");
  }
  
  // Show the current slide
  slides[slideIndex-1].style.display = "block";
  slides[slideIndex-1].className += " active-slide";
}
</script>

