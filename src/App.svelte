<main>
	<div id="background"></div>
</main>

<style>
	main {
		-moz-animation: wrapper 3s forwards;
		-webkit-animation: wrapper 3s forwards;
		-ms-animation: wrapper 3s forwards;
		animation: wrapper 3s forwards;
		height: 100%;
		left: 0;
		position: fixed;
		top: 0;
		width: 100%;
	}

	#background {
		-moz-animation: background 60s linear infinite;
		-webkit-animation: background 60s linear infinite;
		-ms-animation: background 60s linear infinite;
		animation: background 60s linear infinite;
		-moz-backface-visibility: hidden;
		-webkit-backface-visibility: hidden;
		-ms-backface-visibility: hidden;
		backface-visibility: hidden;
		-moz-transform: translate3d(0,0,0);
		-webkit-transform: translate3d(0,0,0);
		-ms-transform: translate3d(0,0,0);
		transform: translate3d(0,0,0);
		background: url(/images/bg.png) bottom left;
		background-repeat: repeat-x;
		height: 100%;
		left: 0;
		opacity: 1;
		position: fixed;
		top: 0;
	}

	#background {
		background-size: 2250px auto;
    	width: 6750px;
	}
	
	@keyframes background {
		0% {
			-moz-transform: translate3d(0,0,0);
			-webkit-transform: translate3d(0,0,0);
			-ms-transform: translate3d(0,0,0);
			transform: translate3d(0,0,0);
		}

		100% {
			-moz-transform: translate3d(-750px,0,0);
			-webkit-transform: translate3d(-750px,0,0);
			-ms-transform: translate3d(-750px,0,0);
			transform: translate3d(-750px,0,0);
		}
	}

	@media (max-width: 3680px) {
		#background {
			background-size: 1500px auto;
			width: 4500px;
		}
	}
	@media (max-width: 768px) {
		#background {
			background-size: 1000px auto;
			width: 2250px;
		}
	}
</style>