<script>
	import '@fontsource/abhaya-libre';
	import '@fontsource-variable/inter';
	// import { onMount } from 'svelte';
	// let fadeIn = false;
	// let slideUp = false;

	// onMount(() => {
	// 	fadeIn = true;
	// 	slideUp = true;
	// });
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<div class="lines">
		<div class="pink-line"><img src="/PinkLine.png" /></div>
		<div class="white-line"><img src="/WhiteLine.png" /></div>
	</div>
	<div class="my-details-container">
		<div class="emily">EMILY DENG</div>
		<div class="subtitle">UX Design / Web Development / Solutions Engineer</div>
		<div class="subtitle">Currently working as a Software Tester at Avalias</div>
		<div class="socials">
			<a href="/Resume.pdf">
				<svg
					class="svg"
					width="24"
					height="24"
					viewBox="0 0 24 24"
					fill="none"
					xmlns="http://www.w3.org/2000/svg"
				>
					<path
						class="path"
						fill-rule="evenodd"
						clip-rule="evenodd"
						d="M18.7452 5.25482C18.0701 4.57992 17.1546 4.20079 16.2 4.20079C15.2454 4.20079 14.3299 4.57992 13.6548 5.25482L5.2548 13.6548C4.59887 14.3336 4.23579 15.2429 4.24377 16.1868C4.25175 17.1307 4.63014 18.0338 5.29746 18.7014C5.96477 19.369 6.86761 19.7478 7.81151 19.7563C8.75542 19.7647 9.66487 19.402 10.344 18.7464H10.3452L10.9416 18.1464C11.1108 17.9818 11.3379 17.8903 11.5739 17.8915C11.8099 17.8928 12.036 17.9867 12.2035 18.153C12.3709 18.3194 12.4663 18.5448 12.4691 18.7809C12.4719 19.0169 12.3819 19.2446 12.2184 19.4148L11.6208 20.016L11.6184 20.0184C10.6057 21.0311 9.23217 21.6 7.8 21.6C6.36782 21.6 4.9943 21.0311 3.9816 20.0184C2.96889 19.0057 2.39996 17.6322 2.39996 16.2C2.39996 14.7678 2.96889 13.3943 3.9816 12.3816L12.3816 3.98162C13.3937 2.96828 14.7668 2.39848 16.199 2.39758C17.6312 2.39668 19.0051 2.96475 20.0184 3.97682C21.0317 4.98888 21.6015 6.36205 21.6024 7.79422C21.6033 9.2264 21.0353 10.6003 20.0232 11.6136L15.8772 15.8772C15.5877 16.1825 15.24 16.4267 14.8546 16.5954C14.4692 16.7641 14.0539 16.8539 13.6333 16.8595C13.2126 16.8651 12.7951 16.7864 12.4053 16.628C12.0156 16.4696 11.6615 16.2347 11.364 15.9372C11.0665 15.6397 10.8317 15.2856 10.6733 14.8959C10.5148 14.5061 10.4361 14.0886 10.4417 13.6679C10.4473 13.2473 10.5371 12.832 10.7058 12.4466C10.8745 12.0612 11.1187 11.7135 11.424 11.424L15.564 7.28282C15.647 7.19682 15.7463 7.12821 15.856 7.08099C15.9658 7.03377 16.0839 7.00889 16.2034 7.00779C16.3229 7.0067 16.4414 7.02942 16.5521 7.07462C16.6627 7.11982 16.7632 7.1866 16.8477 7.27106C16.9323 7.35552 16.9992 7.45598 17.0445 7.56656C17.0898 7.67715 17.1126 7.79565 17.1116 7.91515C17.1106 8.03465 17.0859 8.15276 17.0387 8.26259C16.9916 8.37241 16.9231 8.47175 16.8372 8.55482L12.6972 12.696C12.5715 12.8211 12.4717 12.9696 12.4034 13.1333C12.3352 13.2969 12.2998 13.4723 12.2994 13.6496C12.2989 13.8269 12.3334 14.0025 12.4009 14.1665C12.4683 14.3305 12.5674 14.4795 12.6924 14.6052C12.8174 14.7309 12.966 14.8307 13.1296 14.899C13.2933 14.9672 13.4687 15.0026 13.646 15.003C13.8233 15.0035 13.9989 14.969 14.1629 14.9016C14.3268 14.8341 14.4759 14.7351 14.6016 14.61L18.7464 10.3464C19.4213 9.67132 19.8004 8.75581 19.8004 7.80122C19.8004 6.84663 19.4213 5.93112 18.7464 5.25602"
					/>
				</svg>
			</a>

			<a href="https://www.linkedin.com/in/emilyxdeng/">
				<svg
					class="svg"
					width="24"
					height="24"
					viewBox="0 0 24 24"
					fill="none"
					xmlns="http://www.w3.org/2000/svg"
				>
					<g clip-path="url(#clip0_61_8)">
						<path
							class="path"
							d="M12 0.47998C5.63758 0.47998 0.47998 5.63758 0.47998 12C0.47998 18.3624 5.63758 23.52 12 23.52C18.3624 23.52 23.52 18.3624 23.52 12C23.52 5.63758 18.3624 0.47998 12 0.47998ZM9.17998 16.7748H6.84718V9.26758H9.17998V16.7748ZM7.99918 8.34598C7.26238 8.34598 6.78598 7.82398 6.78598 7.17838C6.78598 6.51958 7.27678 6.01318 8.02918 6.01318C8.78158 6.01318 9.24238 6.51958 9.25678 7.17838C9.25678 7.82398 8.78158 8.34598 7.99918 8.34598ZM17.7 16.7748H15.3672V12.6144C15.3672 11.646 15.0288 10.9884 14.1852 10.9884C13.5408 10.9884 13.158 11.4336 12.9888 11.862C12.9264 12.0144 12.9108 12.2304 12.9108 12.4452V16.7736H10.5768V11.6616C10.5768 10.7244 10.5468 9.94078 10.5156 9.26638H12.5424L12.6492 10.3092H12.696C13.0032 9.81958 13.7556 9.09718 15.0144 9.09718C16.5492 9.09718 17.7 10.1256 17.7 12.336V16.7748Z"
						/>
					</g>
					<defs>
						<clipPath id="clip0_61_8">
							<rect width="24" height="24" fill="white" />
						</clipPath>
					</defs>
				</svg>
			</a>

			<a href="https://github.com/emxdeng">
				<svg
					class="svg"
					width="24"
					height="24"
					viewBox="0 0 24 24"
					fill="none"
					xmlns="http://www.w3.org/2000/svg"
				>
					<path
						class="path"
						d="M12 2C10.6868 2 9.38642 2.25866 8.17317 2.7612C6.95991 3.26375 5.85752 4.00035 4.92893 4.92893C3.05357 6.8043 2 9.34784 2 12C2 16.42 4.87 20.17 8.84 21.5C9.34 21.58 9.5 21.27 9.5 21V19.31C6.73 19.91 6.14 17.97 6.14 17.97C5.68 16.81 5.03 16.5 5.03 16.5C4.12 15.88 5.1 15.9 5.1 15.9C6.1 15.97 6.63 16.93 6.63 16.93C7.5 18.45 8.97 18 9.54 17.76C9.63 17.11 9.89 16.67 10.17 16.42C7.95 16.17 5.62 15.31 5.62 11.5C5.62 10.39 6 9.5 6.65 8.79C6.55 8.54 6.2 7.5 6.75 6.15C6.75 6.15 7.59 5.88 9.5 7.17C10.29 6.95 11.15 6.84 12 6.84C12.85 6.84 13.71 6.95 14.5 7.17C16.41 5.88 17.25 6.15 17.25 6.15C17.8 7.5 17.45 8.54 17.35 8.79C18 9.5 18.38 10.39 18.38 11.5C18.38 15.32 16.04 16.16 13.81 16.41C14.17 16.72 14.5 17.33 14.5 18.26V21C14.5 21.27 14.66 21.59 15.17 21.5C19.14 20.16 22 16.42 22 12C22 10.6868 21.7413 9.38642 21.2388 8.17317C20.7362 6.95991 19.9997 5.85752 19.0711 4.92893C18.1425 4.00035 17.0401 3.26375 15.8268 2.7612C14.6136 2.25866 13.3132 2 12 2Z"
					/>
				</svg>
			</a>
		</div>
	</div>

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
		opacity: 0;
		animation: fadeIn 4s ease-in-out forwards;
	}

	@keyframes fadeIn {
		from {
			opacity: 0;
		}
		to {
			opacity: 1;
		}
	}

	br {
		display: block; /* makes it have a width */
		content: ''; /* clears default height */
		margin-top: -10px; /* change this to whatever height you want it */
	}

	.lines {
		position: fixed;
		top: 200px;
		left: 0;
		z-index: 2;
		opacity: 0.3;
	}

	.pink-line {
		position: relative;
		top: 260px;
		animation: moveLeftToRight 100s linear infinite;
	}

	.white-line {
		animation: moveLeftToRight 60s linear infinite;
	}

	@keyframes moveLeftToRight {
		0% {
			transform: translateX(0);
		}
		50% {
			transform: translateX(100%);
		}
		100% {
			transform: translateX(100%) scaleX(-1); /* Mirroring effect */
		}
	}

	.my-details-container {
		position: relative;
		left: -400px;
		top: 500px;
		z-index: 9999;
	}

	.my-details-container:after {
		content: '';
		position: absolute;
		top: -50px;
		left: -100px;
		width: 150%; /* Set the width to cover the entire container */
		height: 150%; /* Set the height to cover the entire container */
		background: url('/DENG.png') no-repeat;
		background-size: contain;
		z-index: -1; /* Make sure the pseudo-element is behind the content */
	}

	.emily {
		color: black;
		font-family: 'Inter Variable', sans-serif;
		font-size: 20px;
		margin-bottom: 25px;
		position: relative;
	}

	.subtitle {
		color: black;
		font-family: 'Inter Variable', sans-serif;
		font-size: 14px;
		margin-bottom: 20px;
	}

	.svg {
		margin-right: 10px;
	}

	.svg:hover .path {
		fill: #fdc2c1;
	}

	.path {
		fill: black;
	}

	.link {
		font-family: 'Abhaya Libre', serif;
		font-size: 115px;
		font-style: normal;
		font-weight: 500;
		line-height: normal;
		color: white;
		position: relative;
		z-index: 9999;
		left: 330px;
		bottom: -45px;
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
