<script lang="ts">
	import '../app.css';

	const { children } = $props();
</script>

<svelte:head>
	<meta property="og:url" content="https://apocalyptic-roomaji.tktb-tess.dev" />
	<meta property="og:site_name" content="終末式ローマ字" />
	<meta property="og:image" content="/link-card.jpg" />
	<meta name="twitter:image" content="/link-card.jpg" />
	<meta name="twitter:card" content="summary" />
	<meta name="twitter:site" content="@triethylamineq" />
</svelte:head>

{@render children()}
