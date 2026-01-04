<?php include "config.php"; ?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>sweet</title>
</head>
<link rel="stylesheet" href="style.css">
<body>
     <header>
    <nav class="navbar">
            <a href="#"class="nav-logo">
        <h2 class="logo-text">🧇The Sweet Corner</h2>
    
    
           </a>
           <ul class="nav-menu">

        <li class="nav-item">
            <a href="index.php"class="nav-link">Home</a>

        </li>
        <li class="nav-item">
            <a href="aboutus.php"class="nav-link">About Us</a>

        </li>
        <li class="nav-item">
            <a href="menu.php"class="nav-link">Menu</a>

        </li>
        <li class="nav-item">
            <a href="Reviews.php"class="nav-link">Reviews</a>

        </li>
        <li class="nav-item">
            <a href="contactus.php"class="nav-link">contact us
</a>

    

         </ul>   
        
 

    </nav>
   </header> 



    <!--PREMIERE PARTIE-->
    <h3 class="TEXT1">Welcome to our rental shop, where quality service and customer satisfaction come first.</h3>
    <h2 class="TEXT2">About Us:</h2>

   <!--Services Container-->
   <div class="about-us">
    <div class="btns">
        <button id="btn_diva">1</button>
        <button id="btn_divb">2</button>
        <button id="btn_divc">3</button>
    </div>

    <div class="blocks">
  <!-- 1 -->
    <div class="diva" id="diva">
         <div class="about-info">
            <div class="about-info-text">
                <h2>M.karim</h2>
            <p>He is a business owner who manages a rental shop and runs his own business. He provides reliable services and focuses on customer satisfaction. With experience in the field, he is committed to professionalism and quality.</p>
            
            </div>
            
            
             <img class="about-image" src="images/photo_2025-12-25_17-37-20.jpg" alt="">
        </div>     
    </div>


    <!-- 2 -->
    <div class="divb" id="divb">
        <div class="about-info">
            <div class="about-info-text">
                <h2>About Us</h2>
            <p>Our shop started as a small rental business built on trust and dedication. Over time, we grew by focusing on quality service and customer satisfaction. Today, we continue to provide reliable and professional rental solutions.</p>
            
            
            </div>
            
            
             <img class="about-image" src="images/photo_2025-12-25_16-53-24.jpg" alt="">
        </div> 
    </div>

    <!-- 3 -->
    <div class="divc" id="divc">
        <div class="about-info">
            <div class="about-info-text">
                <h2>Our Team</h2>
            <p>Our team is made up of dedicated and experienced professionals who work together to deliver reliable and high-quality rental services. We believe in teamwork, professionalism, and customer satisfaction.</p>
            
            
            </div>
            
            
             <img class="about-image" src="images/photo_2025-12-25_16-54-31.jpg" alt="">
        </div>
          
    </div>
    </div>
   </div>








   <footer class="footer">
  <div class="footer-box">
    <h3>The Sweet Corner</h3>
    <ul>
      <li>Home</li>
      <li>About Us</li>
      <li>Menu</li>
      <li>Reviews</li>
      <li>Contact Us</li>
    </ul>
  </div>

  <div class="footer-box">
    <h3>Contact</h3>
    <p>Email: thesweetcorner21@gmail.com</p>
    <p>Phone: 05 xx xx xx xx</p>
    <p>Address: Rue 21 xxx, Skikda</p>
  </div>

  <div class="footer-box">
    <h3>Suivez-nous</h3>
    <ul>
      <li>Facebook</li>
      <li>Instagram</li>
    </ul>
  </div>
  
</footer>
 <div class="footer-bottom">
    <p><b>© 2026 My Shop. The Sweet Corner.</b></p> </div>



  
  
 .TEXT1{
        text-align: center;
        font-size: 17px;
        margin-top: 30px;
        margin-bottom: 20px;
        color:black;
    }

    .TEXT2{
        text-align: center;
        margin-top: 10px;
        color: black;
    }
  
    .about-us{
      
        margin: 5px auto;
        
        background: #efefef;
        width: 80%;
        height: 350px;
        border-radius: 30px;
    }
    
   .btns{
        display: flex;
        gap: 2px;
        padding-left: 45%;
}

    .btns button{
        border: none;
       background:  rgb(116, 39, 39);
        color: white;
        width: 40px;
        height: 40px;
        border-radius: 20px;
        margin-bottom: 30px;
        cursor: pointer;
    }

      .btns button:hover{
        border: none;
          background-color:rgb(176, 165, 166);
        width: 35px;
        height: 35px;
    }

    .blocks{
        display: flex;
        width: 100%;
        height: 100%;
    }
    .diva{
        width: 100%;
        height: auto;
        display: block;
       
    }

     .divb{
        display: none;
        width: 100%;
        height: auto;
        
     
    }

      .divc{
        display: none;
        width: 100%;
        height: auto;
     
       
    }

 
  .about-info-text{
    width: 40%;
    margin-left: 55px;
    margin-top: 20px;
  }

.about-info{
    display: flex;
}

  .about-image{
    width: 30%;
    height: 30%;
    border-radius: 30px;
    margin-left: 150px;
  }
     <script type="text/javascript" src="script.js"></script>
</body>
</html>
