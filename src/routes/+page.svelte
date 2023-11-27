<script>
	import '@fontsource/abhaya-libre';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<div class="emily"></div>

	<div class="links">
		<a class="link about underline" href="/about">About</a>
	</div>
</section>

<style>
	section {
		display: flex;
	}

	.link {
		font-family: 'Abhaya Libre', serif;
		font-size: 120px;
		font-style: normal;
		font-weight: 500;
		line-height: normal;
		color: white;
		position: relative;
		z-index: 2;
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

	.underline:after {
		content: '';
		position: absolute;
		width: 380px;
		height: 30px;
		margin: auto;
		z-index: -1;
		background-color: #fdc2c1;
		left: -10px;
		bottom: 30px;
	}

	.design::before {
		content: 'Design';
		position: absolute;
		left: 8px;
		color: black;
	}

	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}
</style>
