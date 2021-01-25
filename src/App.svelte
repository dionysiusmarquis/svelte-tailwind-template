<script>
	import './css/tailwind.pcss'

	export let name;
</script>

<main>
	<h1>Hello {name}!</h1>
	<p class="text-green-900">Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<style lang="postcss">
	main {
		@apply p-4;

		text-align: center;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>