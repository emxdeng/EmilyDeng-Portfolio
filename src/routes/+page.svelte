<script>
	import '@fontsource/abhaya-libre';
	import '@fontsource-variable/inter';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<div class="emily"></div>

	<div class="links">
		<a class="link design pink-underline" href="/">Design</a>
		<br />
		<a class="link code green-underline" href="/">Code</a>
		<br />
		<a class="link play blue-underline" href="/">Play</a>
		<br />
		<a class="link about yellow-underline" href="/about">About</a>
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

	br {
		display: block; /* makes it have a width */
		content: ''; /* clears default height */
		margin-top: -10px; /* change this to whatever height you want it */
	}

	.emily {
		font-family: 'Inter Variable', sans-serif;
	}

	.link {
		font-family: 'Abhaya Libre', serif;
		font-size: 115px;
		font-style: normal;
		font-weight: 500;
		line-height: normal;
		color: white;
		position: relative;
		z-index: 2;
		left: 320px;
		bottom: -135px;
	}

	.link:hover {
		text-decoration: none;
		font-style: italic;
	}

	.about:before {
		content: 'About';
		position: absolute;
		left: 8px;
		color: black;
	}

	.design:before {
		content: 'Design';
		position: absolute;
		left: 8px;
		color: black;
	}

	.code:before {
		content: 'Code';
		position: absolute;
		left: 8px;
		color: black;
	}

	.play:before {
		content: 'Play';
		position: absolute;
		left: 8px;
		color: black;
	}

	.pink-underline:after {
		content: '';
		position: absolute;
		width: 380px;
		height: 30px;
		margin: auto;
		z-index: -1;
		background-color: #fdc2c1;
		left: -10px;
		bottom: 35px;
	}

	.green-underline:after {
		content: '';
		position: absolute;
		width: 380px;
		height: 30px;
		margin: auto;
		z-index: -1;
		background-color: #f1f6ef;
		left: -10px;
		bottom: 35px;
	}

	.blue-underline:after {
		content: '';
		position: absolute;
		width: 380px;
		height: 30px;
		margin: auto;
		z-index: -1;
		background-color: #c2d3dc;
		left: -10px;
		bottom: 35px;
	}

	.yellow-underline:after {
		content: '';
		position: absolute;
		width: 380px;
		height: 30px;
		margin: auto;
		z-index: -1;
		background-color: #fdf1f0;
		left: -10px;
		bottom: 35px;
	}
</style>
