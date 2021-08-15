<script>
	import { url } from '@roxi/routify'
</script>

<!-- basic navigation -->
<nav>
	<a href="{$url('./')}">Home</a>
	<a href="{$url('./about')}">About</a>
</nav>
<main>
	<slot />
</main>

<!-- use lang="sass" for SASS -->
<style lang="scss">
	main, nav {
		text-align: center;
		padding: 1em;
	}
	nav a {
		margin: 0 1em;
	}
</style>