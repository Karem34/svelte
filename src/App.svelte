<script>
	import { Router } from "@roxi/routify";
	import { routes } from "./.routify/routes";
</script>

<svelte:head>
	<style lang="scss">
		@import "scss/global.scss";
	</style>
</svelte:head>

<Router {routes} />