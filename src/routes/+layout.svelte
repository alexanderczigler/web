<script>
	import Footer from '../components/Footer.svelte';
	import Header from '../components/Header.svelte';
</script>

<div id="container">
	<Header />
	<slot />
	<Footer />
</div>

<style>
	#container {
		font-family: 'Noto Sans', sans-serif;
		max-width: 800px;
	}
</style>
