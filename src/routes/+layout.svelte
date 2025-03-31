<script lang="ts">
	import Header from '../components/Header.svelte';
	import Footer from '../components/Footer.svelte';
	import '../app.css';

	let { children } = $props();
</script>

<div class="flex-column min-h-full">
	<Header />
	<main class="flex-column m-0 items-center justify-center p-[1rem]">
		{@render children()}
	</main>
	<Footer />
</div>
