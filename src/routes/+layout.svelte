<script>
	import './styles.css';
</script>

<div class="app">
	<main>
		<slot />
	</main>
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

	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
		position: relative;
	}

	.app::before {
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
		opacity: 0;
		animation: fadeInBackground 2s ease-in-out forwards; /* Adjust the duration and timing function as needed */
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
