<script lang="ts">
	import '../app.css';
	import Footer from '$lib/components/footer.svelte';
	let { children } = $props();
</script>

<div class="flex flex-col min-h-screen bg-gradient-to-br from-gray-950 via-gray-800 to-gray-900">
	<main class="flex-grow flex flex-col text-white">
		{@render children()}
	</main>
	<Footer />
</div>