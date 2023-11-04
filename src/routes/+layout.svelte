<script>
	import Header from './Header.svelte';
</script>

<div class="app">
	<Header />

	<main>
		<slot />
	</main>

	<footer>
		<p>&copy; 2023</p>
	</footer>
</div>

<style>
/* root layout style */
</style>
