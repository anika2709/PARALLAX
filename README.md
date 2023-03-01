# PARALLAX
HTML PAGE USING PARALLAX
<!DOCTYPE html>
<html lang="en">

<head>
	<style>

		/* Styling the body */
		* {
			margin: 0px;
			padding: 0px;
		}

		/* Styling the first parallax's
		height, width and background color */
		.parallax-1 {
			width: 100%;
			height: 600px;
			background: url(https://images.unsplash.com/photo-1480714378408-67cf0d13bc1b?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxleHBsb3JlLWZlZWR8Mnx8fGVufDB8fHx8&auto=format&fit=crop&w=2000&q=60);
			background-size: 100% 100%;
			background-attachment: fixed;
		}

		/* Styling the title of first parallax */
		.parallax-1 h2 {
			margin: auto;
			position: relative;
			left: 500x;
			top: 300px;
			width: 250px;
			height: 32px;
			padding: 10px;
			background-color: black;
			color: white;
			text-align: center;
		}

		/* Styling the second parallax's
		height, width and background color */
		.parallax-2 {
			width: 100%;
			height: 600px;
			background: url(https://img.freepik.com/free-photo/cherry-blossoms-fuji-mountain-spring-sunrise-shizuoka-japan_335224-110.jpg?w=826&t=st=1676299048~exp=1676299648~hmac=3d1c8cc2c1fbb351e730c1da1752b124547182e53de3309f7260dd1e4da4a02a);
			background-size: 100% 100%;
			background-attachment: fixed;
		}

		/* Styling the title of second parallax */
		.parallax-2 h2 {
			margin: auto;
			position: relative;
			left: 500x;
			top: 300px;
			width: 250px;
			height: 70px;
			padding: 10px;
			background-color: white;
			color: black;
			text-align: center;
			font-size: 30px;
			font-family: Verdana;
		}
		.parallax-3 {
			width: 100%;
			height: 600px;
			background: url(https://assets.gocity.com/files/groot_london/files/styles/wysiwyg_medium/public/LP_Tower_Bridge%20%281%29.jpg);
			background-size: 100% 100%;
			background-attachment: fixed;
		}

		/* Styling the title of third parallax */
		.parallax-3 h2 {
			margin: auto;
			position: relative;
			left: 500x;
			top: 300px;
			width: 250px;
			height: 32px;
			padding: 10px;
			background-color: black;
			color: white;
			text-align: center;
		}


		/* Styling the content or paragraph */
		.para-1 {
			padding: 50px;
			background-color: black;
			color: white;
			font-size: 17px;
		}

		/* Styling the content or paragraph */
		.para-2 {
			text-align: center;
			padding: 25px;
			font-size: 17px;
			font-family: Verdana;
			background-color: black;
			color: white;
		}
		.para-3 {
			padding: 50px;
			background-color: black;
			color: white;
			font-size: 17px;
		}
	</style>
</head>

<body>

	<!-- Giving title of the first parallax -->
	<div class="parallax-1">
		<h2>ANIKA SAMVEDI 173</h2>
	</div>

	<!--Content of first parallax -->
	<div class="para-1">
		<p>
			What happens when you walk with closed eyes?
			You fall down;
			But the most important thing is that we miss out
			to watch over the things happening in our life.
			The transition in the Parallax shows how life can 
			be full of happening moments in a city with big 
			skyscrapers but at the same time the mind needs to 
			rest under a cherry blossom tree in solitude.
			Thus,depicting two immediate moments of LIFE.
		</p>
	</div>

	<!-- Giving title of the first parallax -->
	<div class="parallax-2">
		<h2>Cherry blossom</h2>
	</div>

	<!--Content of first parallax -->
	<div class="para-2">
		<p>
			But like every other thing in life good things
			don't last forever !
			But still we can strive for the peace and
			the city life making this transition a mixture
			of both POVs.Maintaining the real balance of life!
		</p>
	</div>

	<!--This will be same as first parallax-->
	<div class="parallax-3">
		<h2>A Busy-Peaceful Life?</h2>
	</div>

	<div class="para-2">
		<p>
			 "The best and most beautiful things in the world cannot be seen or even touched — they must be felt with the heart."
			  Helen Keller
		</p>
	</div>
</body>

</html>
