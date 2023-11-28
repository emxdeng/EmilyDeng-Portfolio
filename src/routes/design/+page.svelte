<script>
	// Supports weights 400-700
	import '@fontsource-variable/lora';
</script>

<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<div class="text-column">
	<h1>Design</h1>

	<h2>Blahblah</h2>

	<body> blahlalajfjdkl </body>
</div>

<style>
	.text-column {
		z-index: 3;
		background-color: rgba(255, 255, 255, 0.7);
		padding: 40px;
		position: fixed;
		width: 100%;
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
