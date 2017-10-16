# Online-Car-Parking-System
<!DOCTYPE html>
<!--
To change this license header, choose License Headers in Project Properties.
To change this template file, choose Tools | Templates
and open the template in the editor.
-->
<html>
    <head>
        <title>TODO supply a title</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="css/style.css">
        <link rel="stylesheet" href="css/bootstrap-3.3.7-dist/css/bootstrap.css">
        <link rel="stylesheet" href="css/bootstrap-3.3.7-dist/css/bootstrap.min.css">
        
        <script src="js/jquery-3.2.1.min.js"></script> 
        <script src="css/bootstrap-3.3.7-dist/js/bootstrap.min.js"></script>
        <!--<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>-->
        <script src="js/jquery.min.js"></script>
        <!-- <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>-->
        <script src="js/bootstrap.min.js"></script>
       <script src="js/main.js"></script>        
                  
        
        
    </head>
    <body>
<nav class="navbar transparent navbar-fixed-top navbar-default">
          <div class="container-fluid">
            <div class="navbar-header">
            <a class="navbar-brand" href="#">Car Park</a>
          </div>
          <ul class="nav navbar-nav" id="first">
        <li class="active"><a href="#">Home</a></li>
        <li ><a href="#about" id="link1">About Us</a></li> 
        <li><a href="#features">Features</a></li>
       </ul>
          <ul class="nav navbar-nav navbar-right">
              <li><a href="register2.php"><span class="glyphicon glyphicon-user"></span> Sign Up</a></li>
              <li><a href="login.php"><span class="glyphicon glyphicon-log-in"></span> Login</a></li>
        </ul>
     </div>
</nav>
<!--end of navbar-->

<!--Slider-->
<div id="myCarousel" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
    </ol>
     <div class="carousel-inner">
      <div class="item active">
        <img src="images/2.jpg" alt="image1" style="width:100%;">
         <div class="carousel-caption">
        <h3>Car Parking Service</h3>
        <p>Real time parking spaces search</p>
      </div>
      </div>

      <div class="item">
        <img src="images/1.jpg" alt="parking2" style="width:100%;">
      </div>
    
      <div class="item">
        <img src="images/3.jpg" alt="parking3" style="width:100%;">
      </div>
    </div>

    <!-- Left and right controls -->
    <a class="left carousel-control" href="#myCarousel" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
<!--end of slider-->



<section class="section sectionAbout" id="about">
    <div class="page-header text-center">
        <h1>About Us</h1></div>
</section>
  
<div id="features" class="features
">
<div class="page-header text-center">
        <h1>Features We Offer</h1></div>
</div>
<footer>
    
</footer>
       


       
    </body>
</html>
