<script lang="ts">
	import '../app.css';

	const { children } = $props();
</script>

<svelte:head>
	<meta property="og:url" content="https://shuuro.tktb-tess.dev" />
	<meta property="og:site_name" content="終末式ローマ字" />
	<meta property="og:image" content="/link-card.jpg" />
	<meta name="twitter:image" content="/link-card.jpg" />
	<meta name="twitter:card" content="summary" />
	<meta name="twitter:site" content="@triethylamineq" />
</svelte:head>

<div class="flow-root m-0 px-4 xl:mx-auto xl:max-w-[80rem] border-l border-r border-slate-300">
	{@render children()}
</div>
