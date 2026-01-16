<script lang="ts">
	import favicon from "$lib/assets/favicon.svg";

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>
<header>
	<h1>Git Release Branches Demo</h1>
	<nav>
		<a href="/">Home</a>
	</nav>
	<p>Feature: C</p>
</header>
{@render children()}
