<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
</head>
<body>
    <script src="style.js"></script>
    <img class="image-gradient" src="gradient.png" alt=" gradient ">
    <div class="layer-blur"></div>
    <div class="container"></div>
    <header>
        <h1 data-aos="fade-right" data-aos-duration="1200" class="logo">AkCODE</h1> 

        <nav>
            <a data-aos="fade-down" data-aos-duration="1800" href="# ">COMPANY</a>
            <a data-aos="fade-down" data-aos-duration="2100" href="#">FEATURES</a>
            <a data-aos="fade-down" data-aos-duration="2400" href="#">RESOURCES</a>
            <a data-aos="fade-down" data-aos-duration="2700" href="#">DOCS</a>
        </nav>
      
        <button data-aos="fade-left" data-aos-duration="1200" 
        class="btn-signing">SIGNING</button>
    </header>
    <main>
    <div class="content">
        <div data-aos="fade-zoom-in"
        data-aos-easing="ease-in-back"
        data-aos-delay="300"
        data-aos-offset="0" data-aos-duration="1500" class="tag-box">
            <!--WERBAR SHAPED TO INHANCE STYLING  -->
            <div class="tag">INTRODUCING &wedbar;</div>
        </div>
        <h1 data-aos="fade-zoom-in"
        data-aos-easing="ease-in-back"
        data-aos-delay="300"
        data-aos-offset="0" data-aos-duration="1800">ROBOT FOLLOWING<br>CORSOR</h1>
        <P data-aos="fade-zoom-in"
        data-aos-easing="ease-in-back"
        data-aos-delay="300"
        data-aos-offset="0" data-aos-duration="2200" class="description">
            The robot moves in response to the cursor's movement of the mouse on the screen, allowing for interactive control.
        </P>
        <div class="button">
            <a data-aos="fade-right" data-aos-duration="2800" href="#" class="btn-get-started">Documentation &gt;</a>
            <a data-aos="fade-right" data-aos-duration="2800" href="#" class="btn-signing-mail">Getstarted &gt;</a>
        </div>
    </main>
    <spline-viewer class="robot-3d" url="https://prod.spline.design/5mH3FZR60UtP5CxE/scene.splinecode"></spline-viewer>
    </div>
    <script type="module" src="https://unpkg.com/@splinetool/viewer@1.9.92/build/spline-viewer.js"></script>
    <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
    <script>
      AOS.init();
    </script>
</body>
</html>
