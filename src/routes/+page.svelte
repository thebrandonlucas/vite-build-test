<script lang="ts">
	import { defineCustomElements } from 'bitcoin-qr/loader';

	defineCustomElements();
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<bitcoin-qr
	id="qr"
	width="300"
	height="300"
	bitcoin="BC1QYLH3U67J673H6Y6ALV70M0PL2YZ53TZHVXGG7U"
	parameters="?amount=0.00001&label=sbddesign%3A%20For%20lunch%20Tuesday&message=For%20lunch%20Tuesday"
	image="https://voltage.imgix.net/Team.png?fm=webp&w=160"
	type="svg"
	corners-square-color="#b23c05"
	corners-dot-color="#e24a04"
	corners-square-type="extra-rounded"
	dots-type="classy-rounded"
	dots-color="#ff5000"
/>
