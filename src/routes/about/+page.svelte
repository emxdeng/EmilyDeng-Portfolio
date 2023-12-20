<script>
	// Supports weights 400-700
	import '@fontsource-variable/lora';
</script>

<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
	<h1>About</h1>

	<div class="container">
		<div class="left">
			<h2>About me</h2>
			<p>
				<em>Please note: I am on a subclass 309 partner visa with full working rights.</em>
			</p>
			<p>
				<a
					target="_blank"
					rel="noopener noreferrer nofollow"
					href="https://emojipedia.org/red-heart/">❤️</a
				> I love doing work that helps the community.
			</p>
			<p>
				🤝 My goal is to make a positive difference and enjoy my time with the people I work with.
			</p>
			<p>
				🧠 I have a chemical engineering degree, worked three years in healthcare IT, and currently
				work part-time as a software tester during my studies.
			</p>
			<p>
				I will graduate with a Master of Interaction Design from the University of Technology Sydney
				in November 2023.
			</p>
		</div>
		<div class="right">
			<img
				loading="lazy"
				src="https://storage.googleapis.com/uxfolio/615c95d5df793f0003cd39b9/6229f679e1e659f619e6f3f9/T19YBS2o2ORCsVDM.jpg"
				data-zoom=""
				alt=""
				width="468"
				height="630"
				class="medium-zoom-image"
			/>
		</div>
	</div>

	<br />
	<br />

	<h2>My Values</h2>
	<div class="container">
		<div class="leftmost">
			<h3>⚙️ Problem Solving</h3>
			I create intentional solutions by having meaningful conversations and doing thorough research to
			determine the root cause of an issue.
		</div>

		<div class="center">
			<h3>📚 Always Learning</h3>
			I strive to be flexible, open to change, and constantly growing.
		</div>

		<div class="rightmost">
			<h3>🎨 Creative Thinking</h3>
			I find inspiration from many sources - designs, technology, people, art, music, or nature.
		</div>
	</div>
</div>

<style>
	img {
		border-radius: 10px;
	}

	.container {
		display: flex;
		justify-content: space-between; /* This will create space between the left and right divs */
	}

	.left {
		flex: 1; /* This will make the left div take up available space */
		padding-right: 20px; /* Add some spacing between the left and right divs */
	}

	.right {
		flex: 1; /* This will make the right div take up available space */
	}

	.leftmost,
	.center,
	.rightmost {
		flex: 1; /* This will make each div take up an equal amount of available space */
		padding: 0 10px; /* Add some spacing between the divs */
		box-sizing: border-box; /* Include padding in the width */
	}
	.text-column {
		z-index: 9999;
		background-color: rgba(255, 255, 255, 0.7);
		border-radius: 30px;
		padding: 40px;
		width: 80%;
		height: 80%;
	}

	h1 {
		font-family: 'Lora Variable', serif;
		font-size: 60px;
	}

	h2 {
		font-family: 'Lora Variable', sans-serif;
		font-size: 24px;
		text-transform: uppercase;
		letter-spacing: 3px;
	}

	body {
		font-family: 'Lora Variable', serif;
		font-size: 15px;
	}
</style>
