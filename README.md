# bootstrap-host<!DOCTYPE html>
<html lang="en">
<head>
  <title> Bootstrap Theme </title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  <style>
  body {
    font: 20px Montserrat, sans-serif;
    line-height: 1.8;
    color: #f5f6f7;
  }
  p {font-size: 16px;}
  .margin {margin-bottom: 45px;}
  .bg-1 { 
    background-color: #1abc9c; /* pink */
    color: #ffffff;
  }
  .bg-2 { 
    background-color: #474e5d; /* blue*/
    color: #ffffff;
  }
  .bg-3 { 
    background-color: #ffffff; /* white*/
    color: #555555;
  }
  .bg-4 { 
    background-color: #2f2f2f; /* black */
    color: #fff;
  }
  .container-fluid {
    padding-top: 70px;
    padding-bottom: 70px;
  }
  .navbar {
    padding-top: 15px;
    padding-bottom: 15px;
    border: 0;
    border-radius: 0;
    margin-bottom: 0;
    font-size: 12px;
    letter-spacing: 5px;
  }
  .navbar-nav  li a:hover {
    color: #1abc9c !important;
  }
  </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-default">
  <div class="container">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>                        
      </button>
      <a class="navbar-brand" href="#">My Portfolio</a>
    </div>
    
      </ul>
  </div>
</nav>

<!-- First Container -->
<div class="container-fluid bg-1 text-center">
  <h3 class="margin">Hey there,it's vineet patra</h3>
  <img src="photo.png" class="img-responsive img-circle margin" style="display:inline" alt="flowers" width="350" height="350">
  <h3>A computer science student.</h3>
</div>

<!-- Second Container -->
<div class="container-fluid bg-2 text-center">
  <h3 class="margin">About me</h3>
  <p>My name is VINEET PATRA. I'm a B.Tech student at 
Manav Rachna International Institute of Research and Studies. I am stated in Jammu.I am very passionate about building up businesses.
I like music,sports and cooking.I am also a state level football player.</p>
 
</div>

<!-- Third Container (Grid) -->
<div class="container-fluid bg-3 text-center">    
  <h3 class="margin">Find Me?</h3><br>
  <div class="row">
    <div class="col-sm-4">
      <p>GitHub.</p>
<a href="https://github.com/vineetpatra">
      <img src="git.png" class="img-responsive margin" style="width:100%" alt="Image">
</a>
    </div>
    <div class="col-sm-4"> 
      <p>LinkedIn</p>
<a href="https://www.linkedin.com/in/vineetpatra-789b3b921/">
      <img src="linkedin.png" class="img-responsive margin" style="width:100%" alt="Image">
</a>
    </div>
    <div class="col-sm-4"> 
      <p>Facebook</p>
<a href="https://www.facebook.com/">
      <img src="fb.png" class="img-responsive margin" style="width:100%" alt="Image">
</a>
    </div>
  </div>
</div>



</body>
</html>
