---
title: Welcome
date: Created
layout: base
tags:
  - home
  - welcome
  - info
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio</title>
  <link rel="stylesheet" href="css/style.css">
  <link rel="stylesheet" href="css/nav.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Gloock&family=Raleway:wght@100&display=swap" rel="stylesheet">
</head>
<body>

   <header class="hero">
       <nav class="site-nav">
        <div class="logo">
        Fidel Perez
      </div>
      <a href="#" class="hamburger" id="nav-toggle"><span></span></a>
        <div class="links" id="nav-links">
          <a href="#abo">About</a> 
          <a href="#exp">Experiences</a>
          <a href="#pro">Projects</a>
          <a href="#con">Contact</a>
        </div>
      </nav>
        <h1>Welcome</h1>

   </header>

   <main>
     <section class="About">
      <h2 id="ab">About</h2>
      <img src="https://source.unsplash.com/QJDzYT_K8Xg">
      <p>Hello, My name is Fidel Perez and I am a currently attending school at the Borough of Manhattan Community College. My current major is Multimedia Design.<br> I am learning both web developement and graphic design. I specialize in creating sites using html and CSS. I am familiar in using Adobe suite.</p>
     </section>


    <section class="work">
    <h2>Projects</h2>


   <div class="projects">
    <h3> Postcard </h3>
   <div class="project">
      <img src="img/moma-postcard.jpg">
    </div>  
   </div>
   
  </section>
    <section class="contact">
      <h2>Say Hello</h2>
      <p>To reach out to me just send me an email</p>
     </section>

   </main>

   <footer class="site-footer">
    <div class="footer-description">
      <p>&copy; Designed and Built by Fidel Perez 2023</p>
    </div>

   </footer>
   <script src="https://code.jquery.com/jquery-3.6.3.min.js" integrity="sha256-pvPw+upLPUjgMXY0G+8O0xUf+/Im1MZjXxxgOcBQBXU=" crossorigin="anonymous"></script>
   <!--    Load Local version if CDN is not working-->
   <script>window.jQuery || document.write('<script src="js/vendor/jquery-3.6.3.min.js"><\/script>')</script>
   <!-- Site JavaScript file -->
   <script src="js/main.js"></script>

</body>
</html>
