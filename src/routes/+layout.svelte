<script>
	import '../app.css';
	import NavBar from '../components/NavBar.svelte';
	import '@fontsource/zen-dots';
	import { inject } from '@vercel/analytics';
	import { dev } from '$app/environment';

	inject({ mode: dev ? 'development' : 'production' });
</script>

<div class="h-screen">
	<NavBar />
	<slot />
</div>
