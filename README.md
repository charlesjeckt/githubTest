# githubTest
<!DOCTYPE html> 

<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <title>Adventure</title>
        <!-- ==== CSS ==== -->
        <link rel="stylesheet" href="./style.css">
        <script src="" crossorigin="anonymous"></script>

    </head>
    <body>
        <!-- Navbar-->
        <nav class="navbar">
            
            <h1 class="logo">ADVENTURE</h1>
           <ul class="nav-links">
            
            <li><a class="active" href="#">Home</a></li>
            <li><a href="#" style="color: whitesmoke;">Tours</a></li>
            <li><a href="#"  style="color: whitesmoke;">Explore</a></li>
            <li><a href="#"  style="color: whitesmoke;">About</a></li>
            <li><a class="ctn" href="#"  style="color: whitesmoke;">Contact</a></li>
    
           </ul>
           
           <img src="./images/menu-btn.png" alt="" class="menu-btn">
        </nav> 
    
    
      <header>
        <div class="header-content">
           <h2>Explore The Colourful World</h2>
           <div class="line"> </div>
            <h1>A WONDERFUL GIFT</h1>
            <a href="#" class="ctn">Learn More</a>
       
           
        </div>
      </header>  
<section class="events">
<div class="title">
<h1>Upcoming Events</h1>
<div class="line"></div>
</div>
<div class="row">
<div class="col">
     <img src="./images/lager.jpg" alt="">
     <h4>Everest Camp Trek</h4>
     <p>Loren, ipsum dolor sit amet consectetur adipising elit. Voluptatibus q</p>
     <a href="#" class="ctn">Learn More</a>
</div>
<div class="col">
    <img src="./images/gilbeys3.jpg" alt="">
    <h4>Walking Holidays</h4>
    <p>Loren, ipsum dolor sit amet consectetur adipising elit. Voluptatibus q</p>
    <a href="#" class="ctn">Learn More</a>
</div>
</div>

</section>

<section class="explore">
<div class="explore-content">
    <h1>EXPLORE THE WORLD</h1>
    <div class="line"></div>
<p>Loren, ipsum dolor sit amet consectetur adipising elit. Voluptatibus q ipsum dolor sit amet consectetur adipising elit. Voluptatibus</p>
<br><a href="#" class="ctn">Learn More</a>
</div>

</section>
<section class="tours">
<div class="row">
    <div class="col content-col ">
      <h1>UPCOMING TOURS & DESTINATION</h1>
      <div class="line"></div>
      <p>lorem ipsum dolor sit amet consectetur adipising elit. Consectetur quo lorem ipsum dolor sit amet consectetur adipising elit. Consectetur quo</p>
      <a href="#" class="ctn">Learn More</a>
    </div>
    <div class="col image-col">
        <div class="image-gallery">
            <img src="./images/general.jpeg" alt="">
            <img src="./images/kibao.jpeg" alt="">
            <img src="./images/konyagi.jpeg" alt="">
            <img src="./images/amarula.jpeg" alt="">
            
        </div>
    </div>
</div>
</section>
<section class="footer">
<p>Fifth Avenue, NY 10160, New York USA | Phone: 0748-064-530 | Email: contact@example</p>
<p>Copyright 2020 Outdoor Adventure</p>


</section>



<script>
    const menuBtn = ducument.querySelector('.menu-btn')
    const navlinks = ducument.querySelector('.nav-links')
     
     menuBtn.addEventListener('click',()=>{
       navlinks.classlist.toggle('mobile-menu') 
     }
     ) 

</script> 

    </body>
</html>

