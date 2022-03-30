<!DOCTYPE html>
<html>
  
  
 	<head>
		<meta name="viewport" content="with=device-width, initial-scale=1.0">
		<title>NIRture</title>
		<link rel="stylesheet" type="text/css" href="style.css"/>
		<link rel="preconnect" href="https://fonts.googleapis.com">
		<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
		<link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;500;600&family=Source+Sans+Pro:wght@200;300;400;600;700&display=swap" rel="stylesheet">
		<link rel='stylesheet' href='https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css'>
	</head>
	<body>
		<section class='header'>
			<nav>
				<a href='website.html'><img src='logo.png'></a>
				<h0>NIRture</h0>
				<div class='nav-links' id='navLinks'>
					<i class='fa fa-times' onclick='hideMenu()'></i>
					<ul>
						<li><a href=''>HOME</a></li>
						<li><a href=''>ABOUT</a></li>
						<li><a href=''>PROJECTS</a></li>
						<li><a href=''>TEAM</a></li>
						<li><a href=''>CONTACT US</a></li>
						</ul>
				</div>
				<i class='fa fa-bars' onclick='showMenu()'></i> 
			</nav>
		<div class='text-box'>
			<h1> NIRture </h1>
			<p> 	THE GIFT OF TIME, A WINDOW INTO THE FUTURE </p>
		</div>

		</section>




		<!----- ABOUT US ------>

		<section class='aboutus'>
			<h1> About Us </h1>
			<p>From a diverse range of disciplines, we are a group of students from the University of Cambridge working on a solution to post-operative flap care. <br> Our solution is designed around our users with the goal of creating a solution that saves our clients money and time, with the ultimate goal of predicting flap failure so as to provide better care. <br>Our aim is to provide an affordable solution that makes caring easier and better. <br> Join us on our flap care revolution!
		</section>











		<!--------JavaScript for Toggle Menu -------->
		<script>
			
			var navLinks = document.getElementById('navLinks');

			function showMenu(){
				navLinks.style.right = '0';
			}
			function hideMenu(){
				navLinks.style.right = '-200px';
			}

		</script>
      
    
</html>
