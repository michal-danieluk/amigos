<script>
	//	import Footer from './lib/components/footer.svelte';

	//import Header from './lib/components/header.svelte';
	// import Footer from '$lib/components/footer.svelte';
	import Header from '$lib/components/Header.svelte';
	import '../app.css';
	import Footer from '$lib/components/Footer.svelte';
</script>

<Header />

<slot />

<Footer />
