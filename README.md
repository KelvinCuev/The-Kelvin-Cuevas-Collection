<!doctype html>
<html>
<head>
<title>The Kelvin Cuevas Collection</title>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<style>
	html, body {
		margin: 0;
		padding: 0;
	}
	body {
		font-family: 'Arial', sans serif; 
		font-size: 16px;
		line-height: 24px;
	}
	.container {
		background-image: url("Website Background.jpg");
		background-position: center top;
		background-repeat: no-repeat;
		background-size: cover;
		
		max-width: 1366px;
		margin: auto;
	}
	@media screen and (max-width: 768px) {
		.container {
			background-size: 768px;
		}
	}
	.nav-items {
		display: flex;
		flex-wrap: wrap;
		justify-content: flex-end;
		padding: 24px;
	}
	.bHome, .bAbout, .bCollection, .bBehance {
		text-decoration: none;
		color: white;
		padding: 0 16px;
		font-size: 25px;
	}
	@media screen and (max-width: 768px) {
		.bHome, .bAbout, .bCollection, .bBehance {
			font-size: 20px;
		}
	}
	
	@media screen and (max-width: 320px) {
		.container {
			background-size: 320px;
		}
	}
	.nav-items {
		display: flex;
		flex-wrap: wrap;
		justify-content: flex-end;
		padding: 24px;
	}
	
	@media screen and (max-width: 320px) {
		.bHome, .bAbout, .bCollection, .bBehance {
			font-size: 8px;
		}
	}
	
	.about {
		max-width: 800px;
		margin: auto;
		
		padding-top: 550px;
		padding-bottom: 1000px;
	}
	@media screen and (max-width: 768px) {
		.about {
			padding-top: 250px;
			padding-bottom: 550px;
			max-width: 700px;
			font-size: 14px;
		}
	}
	@media screen and (max-width: 320px) {
		.about {
			padding-top: 50px;
			font-size: 8px;
		}
	}
	.about p {
		color: gray;
		font-weight: bold;
	}
	
	@media screen and (max-width: 320px) {
		.about p {
			padding-top: 1px;
			font-size: 12x;
			line-height: 12px;
		}
	}
	
	@media screen and (max-width: 320px) {
		h1 {
			font-size: 10px;
			margin-bottom: 1px;
			line-height: 14px;	
		}
	}
</style>

<body>
	<div class="container">
		<nav class="nav-items">
			<a class="bHome" href="#A1">Home</a>
			<a class="bAbout" href="#about">About</a>
			<a class="bCollection" href="#collection">Collection</a>
			<a class="bBehance" href="https://www.behance.net/kelvincuevas">Behance</a>
		</nav>
		<div class="about" id="about">
			<h1>ABOUT</h1>
			<p>
				I am Kelvin Lance M. Cuevas and currently a second year student taking a course of Bachelor of Arts in Multimedia Arts. I am  a freelance artist capable to work  for your demands having enthusiasm to collaborate within a team. This portfolio may serve to showcase my products in automotive photography. However, most of my works include graphic design, video editing, 3D modelling, and a hint of 2D animation. Hope to work with you soon!
			</p>
		</div>
		<div class="collection" id="collection">
		
		</div>
	</div>
	
</body>
</html>
