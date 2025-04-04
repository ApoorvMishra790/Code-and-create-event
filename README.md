# Code-and-create-event
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AI Generated Short Story with Slideshow</title>
  
  <!-- External Libraries -->
  <link href="https://cdn.jsdelivr.net/npm/tooltipster@4.2.7/dist/css/tooltipster.bundle.min.css" rel="stylesheet" />
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.10.1/gsap.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/ScrollMagic/2.0.7/ScrollMagic.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/scrollmagic/2.0.7/plugins/animation.gsap.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/tooltipster@4.2.7/dist/js/tooltipster.bundle.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.min.js"></script>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/slick-carousel@1.8.1/slick/slick-theme.css">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Roboto', sans-serif;
      line-height: 1.6;
      background: #1d1d1d;
      color: #fff;
      overflow-x: hidden;
      margin: 0;
    }

    header {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      background-color: rgba(0, 0, 0, 0.7);
      padding: 20px 50px;
      z-index: 1000;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);
    }

    header nav a {
      color: white;
      text-decoration: none;
      margin-right: 30px;
      font-size: 18px;
      text-transform: uppercase;
      transition: color 0.3s ease;
    }

    header nav a:hover {
      color: #ff6600;
    }

    section {
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 50px 20px;
      transition: all 0.5s ease-in-out;
    }

    section:nth-child(even) {
      background: #333;
    }

    section:nth-child(odd) {
      background: #444;
    }

    .content {
      max-width: 900px;
      margin: 0 auto;
    }

    .title {
      font-size: 3rem;
      color: #ff6600;
      margin-bottom: 20px;
      text-shadow: 2px 2px rgba(0, 0, 0, 0.6);
      animation: glow 1.5s ease-in-out infinite alternate;
    }

    @keyframes glow {
      0% {
        text-shadow: 0 0 5px #ff6600, 0 0 10px #ff6600, 0 0 15px #ff6600;
      }
      100% {
        text-shadow: 0 0 20px #ff6600, 0 0 30px #ff6600, 0 0 40px #ff6600;
      }
    }

    .highlight {
      background: rgba(255, 102, 0, 0.2);
      font-weight: bold;
      padding: 3px 5px;
      border-radius: 5px;
      color: #ff6600;
    }

    .paragraph {
      font-size: 1.4rem;
      margin-bottom: 40px;
      opacity: 0.85;
      transition: opacity 0.5s ease;
    }

    .paragraph:hover {
      opacity: 1;
      transition: opacity 0.3s ease-in-out;
    }

    .image {
      max-width: 100%;
      border-radius: 15px;
      margin-bottom: 40px;
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
      transform: scale(0.98);
      transition: transform 0.3s ease-in-out;
    }

    .image:hover {
      transform: scale(1.05);
    }

    /* Image Slideshow Styling */
    .slideshow {
      width: 100%;
      height: 400px;
      margin-bottom: 40px;
    }

    .slick-prev,
    .slick-next {
      color: #ff6600;
    }

    /* Scroll to Top Button */
    #scrollToTop {
      position: fixed;
      right: 20px;
      bottom: 20px;
      background-color: #ff6600;
      color: white;
      border: none;
      padding: 15px;
      font-size: 18px;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      transition: opacity 0.3s ease;
    }

    #scrollToTop.visible {
      display: block;
    }

    .tooltipster-base {
      background-color: #333;
      color: #fff;
      border-radius: 5px;
      font-size: 14px;
      padding: 10px;
    }

  </style>
</head>
<body>

<header>
  <nav>
    <a href="#section1" id="nav1">Introduction</a>
    <a href="#section2" id="nav2">The Journey</a>
    <a href="#section3" id="nav3">The Discovery</a>
    <a href="#section4" id="nav4">Conclusion</a>
  </nav>
</header>

<!-- Sections for the Short Story -->
<section id="section1">
  <div class="content">
    <h2 class="title">The Beginning of the Journey</h2>
    <p class="paragraph">In a small town, nestled between the mountains, a curious child found a mysterious object buried in the forest. Little did they know, this discovery would change their life forever. <span class="highlight">Discover more about this mysterious object!</span></p>
    <div class="slideshow">
      <div><img src="https://via.placeholder.com/800x400?text=AI+Generated+Image+1" class="image" alt="AI-generated Image"></div>
      <div><img src="https://via.placeholder.com/800x400?text=AI+Generated+Image+2" class="image" alt="AI-generated Image"></div>
    </div>
  </div>
</section>

<section id="section2">
  <div class="content">
    <h2 class="title">The Journey Begins</h2>
    <p class="paragraph">As the child held the object, the world around them began to shift. Suddenly, they were no longer in the forest but standing on the edge of a vast desert. The sky was dark with swirling clouds, and the wind howled like a distant cry. <span class="highlight">What happens next?</span></p>
    <div class="slideshow">
      <div><img src="https://via.placeholder.com/800x400?text=AI+Generated+Image+3" class="image" alt="AI-generated Image"></div>
      <div><img src="https://via.placeholder.com/800x400?text=AI+Generated+Image+4" class="image" alt="AI-generated Image"></div>
    </div>
  </div>
</section>

<section id="section3">
  <div class="content">
    <h2 class="title">The Discovery</h2>
    <p class="paragraph">In the desert, the child found an ancient city, its ruins covered in sand. It was here that they made the most astonishing discovery: a hidden chamber with inscriptions in an unknown language. <span class="highlight">What did the inscriptions reveal?</span></p>
    <div class="slideshow">
      <div><img src="https://via.placeholder.com/800x400?text=AI+Generated+Image+5" class="image" alt="AI-generated Image"></div>
      <div><img src="https://via.placeholder.com/800x400?text=AI+Generated+Image+6" class="image" alt="AI-generated Image"></div>
    </div>
  </div>
</section>

<section id="section4">
  <div class="content">
    <h2 class="title">The Conclusion</h2>
    <p class="paragraph">The child learned that their journey was not just about discovering a mysterious object but uncovering the secrets of the past. The journey would lead them to great adventures yet to come. <span class="highlight">The adventure is only beginning!</span></p>
    <div class="slideshow">
      <div><img src="https://via.placeholder.com/800x400?text=AI+Generated+Image+7" class="image" alt="AI-generated Image"></div>
      <div><img src="https://via.placeholder.com/800x400?text=AI+Generated+Image+8" class="image" alt="AI-generated Image"></div>
    </div>
  </div>
</section>

<!-- Scroll to Top Button -->
<button id="scrollToTop">↑</button>

<script>
  // Slick Slideshow
  $(document).ready(function(){
    $('.slideshow').slick({
      autoplay: true,
      autoplaySpeed: 3000,
      arrows: true,
      dots: false,
      fade: true,
      speed: 1000
    });
  });

  // GSAP Animation for Sections
  gsap.from(".section", {
    opacity: 0,
    y: 100,
    duration: 1,
    stagger: 0.3,
    scrollTrigger: {
      trigger: ".section",
      start: "top 75%",
      end: "bottom top",
      scrub: true
    }
  });

  // Scroll to Top Button Visibility
  const scrollToTopButton = document.getElementById('scrollToTop');
  window.addEventListener('scroll', () => {
    if (window.scrollY > 200) {
      scrollToTopButton.classList.add('visible');
    } else {
      scrollToTopButton.classList.remove('visible');
    }
  });

  scrollToTopButton.addEventListener('click', () => {
    window.scrollTo({ top: 0, behavior: 'smooth' });
  });

  // Tooltipster Initialization for Facts
  $(document).ready(function() {
    $('.highlight').tooltipster({
      theme: 'tooltipster-light',
      side: 'top',
      animation: 'fade',
      delay: 200
    });
  });
</script>

</body>
</html>
