<script>
	import { pokemon } from '../stores/pokeStore';
</script>

<svelte:head>
	<title>Svelte Kit Pokedex</title>
</svelte:head>

<h1>Pokedex</h1>

{#each $pokemon as poke}
	<p>{poke.name}</p>
{/each}
