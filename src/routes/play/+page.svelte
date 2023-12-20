<script>
	// Supports weights 400-700
	import '@fontsource-variable/lora';
</script>

<svelte:head>
	<title>Play</title>
	<meta name="description" content="About my hobbies" />
</svelte:head>

<div class="text-column">
	<body>
		<h1>Play</h1>

		<h2>🎤 Singing</h2>

		<p>
			I love making covers in collaboration with other artists. Here's are some examples my singing!
		</p>
		<h3>Example 1: Seeds Cover (English)</h3>
		<p>
			<audio controls>
				<source src="Seeds.mp3" type="audio/mpeg" />
				Your browser does not support the audio element.
			</audio>
		</p>
		<p><em>Additional Credits:</em></p>
		<ul>
			<li>
				mix:
				<a target="_blank" href="https://linktr.ee/hampancake ">Lily Chen (ham)</a>
			</li>
			<li>
				<p>
					original song: <a
						target="_blank"
						rel="noopener noreferrer nofollow"
						href="https://www.youtube.com/c/dearlittlefoxx">Foxi</a
					>
				</p>
			</li>
		</ul>

		<h3>Example 2: Odo Cover (Japanese)</h3>
		<p>
			<audio controls>
				<source src="odo.mp3" type="audio/mpeg" />
				Your browser does not support the audio element.
			</audio>
		</p>
		<p><em>Additional Credits:</em></p>
		<ul>
			<li>
				mix:
				<a target="_blank" href="https://vgen.co/rorekk ">rorekk</a>
			</li>
			<li>
				<p>
					original song: <a
						target="_blank"
						rel="noopener noreferrer nofollow"
						href="https://www.youtube.com/watch?v=YnSW8ian29w">Giga & Ado</a
					>
				</p>
			</li>
		</ul>

		<h2>🎥 Video Editing</h2>
		<p>
			I have been editing videos in collaboration with other creators for 10+ years as a hobbyist
			and have also done casual freelance work for YouTubers. I love editing because it brings
			unique stories and emotions through motion and color.
		</p>

		<h3>Example 1: English Lyric Video with Motion Graphics</h3>
		Edited in Adobe After Effects
		<br />
		Artwork by vidosprout

		<p>
			<img src="/hamday_compressed.gif" alt="Preview of the video" class="video-gif" />
		</p>

		<h3>Example 2: Japanese Lyric Video with Motion Graphics</h3>
		Edited in Adobe After Effects
		<br />
		Artwork by acarinexacca
		<p>
			<img src="/naimono_compressed.gif" alt="Preview of video" class="video-gif" />
		</p>

		<!-- <h3>Example 3: Unmind University Project</h3>
		Edited in Adobe Premiere Pro + After Effects
		<br />
		Narration and audio editing also done by me
		<p>
			<iframe src="https://www.youtube.com/watch?v=V1tToVDzxho"></iframe>
		</p> -->
		<!-- <h3>Example 4: CulturePop University Project</h3>
		Edited in Adobe Premiere Pro + After Effects (my edits start from 1:18)
		<br />
		Audio clean-up and editing also done by me
		<p>
			<iframe src="https://youtu.be/JDIqlSkgIFY?si=BAY1c_tHVL9gWlEy"></iframe>
		</p> -->

		<h2>🎨 Art</h2>
		<p>
			Digital art is a recent hobby that I have been picking up :) It's fun to explore because
			there's so much to learn. I draw with Procreate on iPad with Apple Pencil.
		</p>

		<h3>Example 1: Twitch Assets Illustration</h3>
		<p>I drew a custom character and emote set for my partner to use for his streaming.</p>
		<img
			src="Clues_Showcase.png"
			style="width:100%"
			alt="Custom character and emote set showcase"
		/>

		<br />

		<h3>Example 2: Character Illustration</h3>
		<p>
			I drew some character illustrations to be used for a song cover in progress with a friend.
		</p>

		<img src="Rimokon_Showcase.png" style="width:100%" alt="Illustration showcase" />

		<!-- <h2>🎧 Audio Mixing</h2>
		<p>My love for singing means I also enjoy editing audio occasionally!</p>
		<p>I did the vocal autotune and mix/master for the linked video using Melodyne and REAPER.</p>
		<p>
			<iframe
				src="https://www.youtube.com/embed/1QS985XPh0k?autoplay=0&amp;mute=0&amp;loop=0"
				loading="lazy"
				frameborder="0"
			></iframe>
		</p>
		<p><em>Additional Credits:</em></p>
		<ul>
			<li>original song by Mitchie M</li>
			<li>vocals: Maria, Shelly, Christine, Lily, and me</li>
			<li>vocal timing & harmony guide: Maria</li>
		</ul> -->
	</body>
</div>

<style>
	.video-gif {
		width: 100%;
		border-radius: 10px;
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
