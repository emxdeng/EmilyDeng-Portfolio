<script>
	// Supports weights 400-700
	import '@fontsource-variable/lora';
</script>

<svelte:head>
	<title>PX Resources</title>
	<meta name="description" content="About my hobbies" />
</svelte:head>

<div class="text-column">
	<body>
		<img
			src="https://storage.googleapis.com/uxfolio/615c95d5df793f0003cd39b9/636f5456e9adcd000347e184/4m7PLvZN5dSTxYuL.png"
			style="width:100%"
		/>
		<h1>PX Resources</h1>

		<div class="text-container align-text-left">
			<h3>PX Resources: A Risk &amp; Compliance Recruitment Firm</h3>
			<p>
				I worked closely with PX Resources' CEO, David Bakes, to define his brand, design his
				website, and build/develop the final product
			</p>
			<p>
				This website acts as the main landing page for PX Resources, where potential clients first
				learn about the company's product and values.
			</p>
			<p>
				My primary goals were to make the process as <strong>smooth, quick, and easy </strong>as
				possible for the client and to build a website that matched
				<strong>his vision and goals </strong>for PX Resources.
			</p>
			<h4><strong>Project Length: </strong>2 months // 3-5 hours per week</h4>
			<p><strong>Skills Used:</strong></p>
			<ul>
				<li><p>Sketching and wireframing in Procreate</p></li>
				<li><p>Squarespace website design and development</p></li>
				<li><p>Figma and Canva for the creation of graphics</p></li>
				<li><p>HTML/CSS</p></li>
				<li><p>Client communication</p></li>
			</ul>
			<p><strong>Lessons Learned:</strong></p>
			<ul>
				<li><p>Importance of designing for multiple screen sizes</p></li>
				<li>
					<p>
						One small task can always become many tasks. I should prioritise the client's needs and
						timeline and suggest new solutions if it's impossible within the timeframe.
					</p>
				</li>
				<li>
					<p>
						Work may need to be redone from scratch from time to time - a website's content is
						always a work in progress, and it's best not to get attached to one version.
					</p>
				</li>
			</ul>
		</div>

		<blockquote>
			<p class="quote">
				"Emily was excellent with the development of our company website. Right from the outset, she
				was detailed and really listened to our requirements. She was creative and proactive with
				solutions and really opened our mind to the possibilities we could have. The end result is
				nothing short of excellent and we would highly recommend Emily if you are looking to develop
				of build something that is outside the box."
			</p>
			<p class="author">- David Bakes, PX Resources CEO</p>
		</blockquote>

		<h2>1. Intro</h2>

		<p>
			David approached me to design and develop his PX Resources website, and we started the
			conversation by discussing his branding, intentions, and ideal timeline.
		</p>

		<p class="emphasis">
			David and I continued to have touch bases weekly to bi-weekly. With each meeting, I summarized
			our conversations and created a Google Drive folder to keep notes, ideas, and deliverables in
			one place. Given the time we had, I suggested we use a customizable website builder.
			Ultimately, we selected SquareSpace based on the ability to customise CSS and the resources
			available for learning it quickly.
		</p>

		<div class="container">
			<div class="left">
				<h2>2. Brand</h2>

				<p>Length: 2 weeks</p>

				<p>
					David's branding was in its early stages when we began working together, so we first
					worked to develop his company brand for the website. I took detailed notes during our
					conversations and presented to him a list of keywords and color schemes that would match
					his concepts.
				</p>

				<p class="emphasis">
					Some keywords that came up were:
					<br />
					Positive: Sophisticated, upmarket, conservative, vivid, bright
					<br />
					Negative: Old school, plain, basic, square
					<br />
					The colors brought up were: white, navy, grey
				</p>
				<p>
					I proposed a few popular color schemes that included what we discussed in our meetings.
					Ultimately we used the keywords to select the final color scheme and create the logo.
				</p>
			</div>
			<div class="right">
				<img
					src="https://storage.googleapis.com/uxfolio/615c95d5df793f0003cd39b9/636f5456e9adcd000347e184/KGgzjwUXynLLlIN7.png"
					style="width:100%"
				/>
			</div>
		</div>
	</body>
</div>

<style>
	.container {
		display: flex;
		justify-content: space-between; /* This will create space between the left and right divs */
	}

	img {
		border-radius: 10px;
	}

	.left {
		flex: 1; /* This will make the left div take up available space */
		padding-right: 20px; /* Add some spacing between the left and right divs */
	}

	.right {
		flex: 1; /* This will make the right div take up available space */
	}

	.quote {
		font-size: 20px;
		margin-top: 30px;
		margin-bottom: 10px;
	}

	.author {
		margin-bottom: 30px;
		font-weight: bold;
	}

	.emphasis {
		font-size: 18px;
	}

	img {
		border-radius: 10px;
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
		margin-top: 80px;
		font-family: 'Lora Variable', sans-serif;
		font-size: 24px;
		text-transform: uppercase;
		letter-spacing: 3px;
	}

	h3 {
		margin-top: 40px;
	}

	body {
		font-family: 'Lora Variable', serif;
		font-size: 15px;
	}

	* {
		box-sizing: border-box;
	}
</style>
