<script>
	import './styles.css';
</script>

<div class="app">
	<div class="background">
		<meta name="viewport" content="width=device-width, initial-scale=1.0" />
		<main>
			<slot />
		</main>
	</div>
</div>

<style>
	@keyframes fadeInBackground {
		from {
			opacity: 0;
		}
		to {
			opacity: 1;
		}
	}

	@media screen and (max-width: 480px) {
		.background {
			display: flex;
			flex-direction: column;
			min-height: 100vh;
			position: relative;
			top: 380px;
			left: 50px;
		}
	}

	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
		position: relative;
	}

	.background::before {
		content: '';
		position: absolute;
		top: 0;
		right: 0;
		bottom: 0;
		left: 0;
		background-image: url('/Background.jpg');
		background-size: auto 100%;
		background-position: center;
		background-repeat: no-repeat;
		max-width: 100%;
		opacity: 0;
		animation: fadeInBackground 1s ease-in-out forwards; /* Adjust the duration and timing function as needed */
	}

	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 64rem;
		margin: 0 auto;
		box-sizing: border-box;
	}
</style>
