# dimidala.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <!-- Theme Made By www.w3schools.com - No Copyright -->
  <title>Name here</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
  <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">


  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
  <style>
  body {
      font: 20px Montserrat, sans-serif;
      line-height: 1.8;
      color: #f5f6f7;
  }
  p {font-size: 16px;}
  .margin {margin-bottom: 45px;}
  .bg-1 { 
      background-color: #1abc9c; /* Green */
      color: #ffffff;
  }
  .bg-2 { 
      background-color: #474e5d; /* Dark Blue */
      color: #ffffff;
  }
  .bg-3 { 
      background-color: #ffffff; /* White */
      color: #555555;
  }
  .bg-4 { 
      background-color: #2f2f2f; /* Black Gray */
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
  li{
    font-size: 14px;
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
      <a class="navbar-brand" href="#">NAME HERE</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#">WHO</a></li>
        <li><a href="#">WHAT</a></li>
        <li><a href="#">WHERE</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- First Container -->
<div class="container-fluid bg-1 text-center">
  <h3 class="margin">Who Am I?</h3>
  <h3>Here is some stuff about me</h3>
  <div style="width:500px;margin:0 auto;text-align:left;">
  <p >

    <ul>
      <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit. </li>
      <li>Integer consequat cursus nibh, vitae mattis ex faucibus ut.</li>
      <li> Curabitur varius dui ac volutpat elementum. Donec quis vulputate enim.</li>
    </ul>
  </p>
  </div>
</div>

<!-- Second Container -->
<div class="container-fluid bg-2 text-center">  
  <h3 class="margin">Contact</h3>

  <div class="bg-1" style="width:40% ;height:70%; margin:0 auto;text-align:left;padding-left:5px;">

      <a style="color:white;" href="#"><div style="padding-left:10px;font-size:36px; " class="fa fa-github-square"></div>  Github: myGithubUser</a> <br />
      <a style="color:white;" href="#"><div style="padding-left:10px; " class="fa fa-mail-forward " ></div></a>  Email: thisBeMy@email.edu <br />
      <a style="color:white;" href="#"> <div style="padding-left:10px; " class="fa fa-phone"></div> Phone: (666)-111-1111 </a> <br />
      <a style="color:white;" href="#"> <div style="padding-left:10px; " class="fa fa-address-card-o"></div> Resume </a> <br />
  </div> 
</div>

<!-- Third Container (Grid) -->
<div class="container-fluid bg-3 text-center">    
  <h3 class="margin">Some of my projects</h3><br>
  <div class="row">
    <div class="col-sm-4">
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      <img src="https://upload.wikimedia.org/wikipedia/en/thumb/a/a7/React-icon.svg/320px-React-icon.svg.png" class="img-responsive margin" style="width:100%" alt="Image">
    </div>
    <div class="col-sm-4"> 
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      <img src="http://zewaren.net/site/sites/default/files/imagepicker/1/FlaskLogo.png" class="img-responsive margin"
       style="width:100%" alt="Image">
    </div>
    <div class="col-sm-4"> 
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      <img src="https://avatars2.githubusercontent.com/u/15658638?v=4&s=400" class="img-responsive margin" 
      style="width:100%height:70%" alt="Image">
    </div>
  </div>
</div>



</body>
</html>
