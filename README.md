<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Okavi Coffee</title>
	<link rel="stylesheet" type="text/css" href="okavi.css">
	<link href="https://fonts.googleapis.com/css2?family=Aladin&family=Bebas+Neue&family=Viga&display=swap" rel="stylesheet">
	<script defer src="https://use.fontawesome.com/releases/v5.14.0/js/all.js"></script>
	<link rel="stylesheet" href="owlcarousel/css/owl.carousel.min.css">
	<link rel="stylesheet" href="owlcarousel/css/owl.theme.default.min.css">
	<!-- <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">
	<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-U1DAWAznBHeqEIlVSCgzq+c9gqGAJn5c/t99JyeKa9xxaYpSvHU5awsuZVVFIhvj" crossorigin="anonymous"></script>  -->
</head>
<body>
	<!-- Header -->
	<div class="header">
		<div class="container">
			<div class="row">
				<div class="col-4">
					<div class="logo">
						<h1>Hidden Coffee</h1>
					</div>
				</div>
				<div class="col-4">
					<div class="menu">
						<ul>
							<li><a href="#home">Home</a></li>
							<li><a href="#about">About</a></li>
							<li><a href="#menu">Menu</a></li>
							<li><a href="#contact">Contact</a></li>
						</ul>
					</div>
				</div>
				<div class="col-4">
					<div class="form">
						<form>
							<input class="search" type="text" placeholder="cari...">
							<a class="button" href="#">
								<i class="fas fa-search"></i>
							</a>
						</form>
					</div>
				</div>
			</div>
		</div>
	</div>
	<!-- Penutup Banner -->

	<!-- Banner Video -->
	<div id="home" class="banner">
		<video autoplay loop muted>
			<source src="kopi.mp4">
			</video>
			<!-- <img src="5.jpg"> -->
			<h1>HIDDEN COFFEE</h1>
			<h3>EXCLUSIVE COFFEE BLENDS</h3>
			<h4>Washington DC, Amerika Serikat</h4>
			<h5>Jam operasional 09:00-21:00</h5>
			<h6>Call (+62)821989816</h6>
		</div>
		<!-- Pentup Banner Video -->

		<!-- Parallax -->		
		<div class="parralax">
			<div id="about" class="container">
				<h2>About</h2>
				<br>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
					tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
					quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
					consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
					cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
					proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
					Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
					tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
					quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
					consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
					cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
				proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
			</div>
		</div>
		<!-- Penutup Parallax -->		
		<br>
		<!-- Menu -->		
		<div id="menu" class="owl-carousel owl-theme">
			<br>
			<h2>Menu</h2>
			<br>
			<div class="item">
				<div id="zoom-in">
					<figure>
						<a href="file:///C:/Users/GTX/Desktop/les%20coding/menu-1.html#"><img src="10 (2).jpg"></a>
						<br>
						<h2 style="font-size: 30px;">Cortado</h2>
						<br>
						<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
							tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
						</p>
					</figure>
				</div>	
			</div>
			<div class="item">
				<div id="zoom-in">
					<figure>
						<a href="https://www.google.com/"><img src="10 (5).jpg"></a>
						<br>
						<h2 style="font-size: 30px;">Macchiato</h2>
						<br>
						<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
							tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
						</p>
					</figure>
				</div>
			</div>
			<div class="item">
				<div id="zoom-in">
					<figure>
						<a href="https://www.youtube.com/"><img src="10 (6).jpg"></a>
						<br>
						<h2 style="font-size: 30px;">Americano</h2>
						<br>
						<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
							tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
						</p>
					</figure>
				</div>
			</div>
			<div class="item">
				<div id="zoom-in">
					<figure>
						<a href="https://www.google.com/"><img src="10 (7).jpg"></a>
						<br>
						<h2 style="font-size: 30px;">Mochaccino</h2>
						<br>
						<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
							tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
						</p>
					</figure>
				</div>
			</div>
		</div>
		<script src="owlcarousel/js/jquery.min.js"></script>
		<script src="owlcarousel/js/owl.carousel.js"></script>
		<script>
			var owl = $('.owl-carousel');
			owl.owlCarousel({
				loop:true,
				nav:true,
				margin:10,
				responsive:{
					0:{
						items:1
					},
					600:{
						items:3
					},            
					960:{
						items:5
					},
					1200:{
						items:6
					}
				}
			});
			owl.on('mousewheel', '.owl-stage', function (e) {
				if (e.deltaY>0) {
					owl.trigger('next.owl');
				} else {
					owl.trigger('prev.owl');
				}
				e.preventDefault();
			});
		</script>
		<!-- Penutup Menu -->

		<!-- Contact -->
		<div id="contact" class="contact">
			<div class="container">
				<div class="row">
					<div class="col-4">
						<div class="box">
							<img src="fotoku.jpg" alt="Ardyanto W.S." />
						</div>
					</div>
					<div class="col-8">
						<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
							tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
							quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
							consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
						cillum dolore eu fugiat nulla pariatur.</p>		
					</div>		
				</div>
			</div>
		</div>	

		<div class="bottom">
			<div class="container">
				<div class="row">
					<div class="col-4">
						<a class="ig" href="#">
							<i class="fab fa-twitter-square"></i>
						</a>
						<h3>@Ardyans</h3>
					</div>
					<div class="col-4">
						<a class="ig" href="http://ardyanswebsite.000webhostapp.com/">
							<i class="fas fa-blog"></i>
						</a>
						<h3>@Ardyans</h3>
					</div>
					<div class="col-4">
						<a class="ig" href="https://www.instagram.com/ardyyannnn/">
							<i class="fab fa-instagram-square"></i>
						</a>
						<h3>@Ardyans</h3>
					</div>
				</div>
			</div>
		</div>
	</body> 
	</html>
