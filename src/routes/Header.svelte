<script lang="ts">
	import { page } from '$app/stores';
</script>

<header id="header">
	<h1 id="title"><a href="/" id="title-link">lucasormerod.com</a></h1>
</header>

<style>
	#header {
		display: flex;
		align-items: center;
		justify-content: space-between;
		position: relative;
		padding: 1rem;
	}

	#title {
		margin: 0;
		text-align: center;
		flex: 1;
		font-weight: 500;
		font-size: 2rem;
	}

	#title-link {
		text-decoration: none;
		color: black;
	}

	#title-link:hover {
		text-decoration: none;
	}
</style>