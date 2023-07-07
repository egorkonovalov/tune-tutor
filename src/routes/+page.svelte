<script lang="ts">
	import MusicLibrary from 'music-library-service';

	let songUrl = '';
</script>

<form action="submit">
	<input type="text" placeholder="Insert song url" bind:value={songUrl} />
	<button type="submit">Get the song</button>
</form>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
