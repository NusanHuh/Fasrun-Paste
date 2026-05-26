<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.ico';
	
	import "@fontsource/mona-sans/400.css";
	import "@fontsource/mona-sans/500.css";
	import "@fontsource/mona-sans/600.css";
	import "@fontsource/mona-sans/700.css";
	import "@fontsource/mona-sans/900.css";

	import "@fontsource/fira-code/300.css";

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>
{@render children()}
