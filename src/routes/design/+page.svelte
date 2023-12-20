<script>
	// Supports weights 400-700
	import '@fontsource-variable/lora';
	// Supports weights 300-800
	import '@fontsource-variable/merriweather-sans';
</script>

<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<section>
	<div class="background-color">
		<div class="text-column">
			<div class="title">
				<a href="/">
					<img src="/BackArrow.png" class="back-arrow" alt="back arrow to return to homepage" />
				</a>
				<h1 class="design pink-underline">Design</h1>
			</div>

			<div class="projects">
				<div class="project">
					<h2>
						<a href="design/pxresources">PX Resources</a>
					</h2>
					<h3>Commercial - SquareSpace Website - Branding | Design | Development</h3>
				</div>

				<div class="project">
					<h2>
						<a href="/">Stylit</a>
					</h2>
					<h3>Personal - Mobile App - Research | Design | Prototyping</h3>
				</div>

				<div class="project">
					<h2>
						<a href="/">Aches Album</a>
					</h2>
					<h3>Personal - Probe Kit - 2 Week Research Project</h3>
				</div>
				<div class="project">
					<h2>
						<a href="/">Pantree</a>
					</h2>
					<h3>Personal - Mobile App - Research | Design | Prototyping</h3>
				</div>
				<div class="project">
					<h2>
						<a href="/">Unmind</a>
					</h2>
					<h3>Personal - Mobile App - Research | Design | Prototyping</h3>
				</div>
			</div>
		</div>
	</div>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	.background-color {
		position: fixed;
		top: 0;
		right: 0;
		bottom: 0;
		left: 0;
		background-color: rgba(255, 255, 255, 0.7);
	}

	.title {
		position: relative;
		bottom: 80px;
	}

	.projects {
		position: relative;
		bottom: 120px;
	}

	.project:before {
		content: '';
		position: absolute;
		width: 380px;
		height: 30px;
		margin: auto;
		z-index: -1;
		background-color: black;
		left: -20px;
		bottom: 35px;
	}

	.back-arrow {
		position: relative;
		scale: 100%;
		top: 230px;
		opacity: 80%;
		z-index: 9999;
	}

	.back-arrow:hover {
		opacity: 100%;
	}

	.text-column {
		position: relative;
		z-index: 3;
		padding: 40px;
		position: fixed;
		width: 50%;
		left: 25%;
		top: -80px;
	}

	h1 {
		font-family: 'Abhaya Libre', serif;
		font-style: normal;
		font-weight: 500;
		line-height: normal;
		color: white;
		position: relative;
		z-index: 9999;
		bottom: -45px;
		font-size: 6vw;
		left: 0px;
	}

	.design:before {
		font-size: 6vw;
		left: 12vw;
	}

	.pink-underline:after {
		left: 10.5vw;
		top: 9vh;
	}

	h2 {
		font-family: 'Lora Variable', sans-serif;
		font-size: 3vw;
		text-transform: uppercase;
		letter-spacing: 0px;
		color: black;
		margin-bottom: 0px;
	}

	h3 {
		font-family: 'Merriweather Sans Variable', sans-serif;
		font-size: 1.2vw;
		font-weight: 300;
		margin-top: 10px;
	}

	body {
		font-family: 'Lora Variable', serif;
		font-size: 15px;
	}
</style>
