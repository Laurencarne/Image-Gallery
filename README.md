# Image-Gallery
<!DOCTYPE html>
<html>
<head>
	<title>Image Gallery</title>
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
	<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.5.0/css/all.css" integrity="sha384-B4dIYHKNBt8Bc12p+WXckhzcICo0wtJAoU8YZTY5qE0Id1GSseTk6S+L3BlXeVIU" crossorigin="anonymous">
	<link href="https://fonts.googleapis.com/css?family=KoHo:400,700" rel="stylesheet">
	<link rel="stylesheet" type="text/css" href="IMGS.css">
</head>
<body>

<!--NAVBAR-->

<nav class="navbar navbar-inverse">
  <div class="container">
    <!-- Brand and toggle get grouped for better mobile display -->
    <div class="navbar-header">
      <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1" aria-expanded="false">
        <span class="sr-only">Toggle navigation</span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
      </button>
      <a class="navbar-brand" href="#"><i class="fas fa-camera-retro"></i> IMGS</a>
    </div>

    <!-- Collect the nav links, forms, and other content for toggling -->
    <div class="collapse navbar-collapse" id="bs-example-navbar-collapse-1">
      <ul class="nav navbar-nav">
        <li class="active"><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
      <ul class="nav navbar-nav navbar-right">
        <li><a href="#">Login <i class="fas fa-user"></i></a></li>
        <li><a href="#">Sign Up <i class="fas fa-user-plus"></i></a></li>
      </ul>
    </div><!-- /.navbar-collapse -->
  </div><!-- /.container-fluid -->
</nav>

<!--JUMBOTRON-->

	<div class="container">
		<div class="jumbotron">
			<h1><i class="fas fa-camera-retro"></i> The Image Gallery</h1>	
			<p>A bunch of beautiful images that I didn't take...</p>
		</div>
	</div>

<!--IMAGES-->
<div class="container">
	<div class="row">
		<div class="col-sm-4"><img src="https://images.unsplash.com/photo-1528224564567-1611757a2909?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=aadbdd8f25f97763cf41012eafa4d76e&auto=format&fit=crop&w=684&q=80" class="img-rounded image1"></div>
		<div class="col-sm-4"><img src="https://images.unsplash.com/photo-1502124448981-823ba9f8ac92?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=4e636d0b56e1922bdfe614b32616d6ec&auto=format&fit=crop&w=334&q=80" class="img-rounded image1"></div>
		<div class="col-sm-4"><img src="https://images.unsplash.com/photo-1518834107812-67b0b7c58434?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=208bfc67ee34b1e0b3ed449c9ad2af3d&auto=format&fit=crop&w=375&q=80" class="img-rounded image1"></div>
		<div class="col-sm-4"><img src="https://images.unsplash.com/photo-1483931430372-226f194be3a5?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=19f1d6c690b57fd731a62112d9065760&auto=format&fit=crop&w=1050&q=80" class="img-rounded image1" class="image-imagel"></div>
		<div class="col-sm-4"><img src="https://images.unsplash.com/photo-1438116356317-4a94d22e3f15?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=1caeda037bedd92d0259a9fb52c031a3&auto=format&fit=crop&w=1050&q=80" class="img-rounded image1"></div>
		<div class="col-sm-4"><img src="https://images.unsplash.com/photo-1495926048989-432065eaae46?ixlib=rb-0.3.5&s=be00a59c097501299ecd536fe70d6ef8&auto=format&fit=crop&w=975&q=80" class="img-rounded image1"></div>
	</div> 
</div>

<!--JAVA and JQUERY Script-->

<script src="https://code.jquery.com/jquery-3.3.1.js"
  integrity="sha256-2Kok7MbOyxpgUVvAk/HJ2jigOSYS2auK4Pfzbm7uH60="
  crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
</body>
</html>
