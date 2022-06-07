<script>
	
</script>

<main>
	<!-- Gotta fix the icon before placing-->
	<!-- <img src="/favicon/apple-touch-icon.png" alt="Mobifolio Logo" width="315" height="315">  -->

	<div id="container">

	</div>
	
</main>

<style>
	/* Change background color (#191414) */
	:global(body) {
		background-color: #191414;
	}

	/* Mobile */
	#container {
		/*Create border for container*/
		border: 1px solid #1DB954;

		/*Change border radius*/
		border-radius: 5px;

		/*Change padding*/
		padding: 4%;

		/*Change margin*/
		margin: 10px;
	}

	/* Tablet */
	@media only screen and (max-width: 600px) {
		#container {
			border: 1px solid #1DB954;
			border-radius: 5px;
			padding: 3%;
			margin: 10px;
		}
	}

	/* Desktop */
	@media only screen and (max-width: 900px) {
		#container {
			border: 1px solid #1DB954;
			border-radius: 5px;
			padding: 2%;
			margin: 10px;
		}
	}
</style>