<script lang="ts">
	import Nav from '../components/nav.svelte';
</script>

<dir class="p-8 max-w-6xl mx-auto">
	<Nav />
	<slot />
</dir>

<style>
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
</style>
