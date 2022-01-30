<script>
	// export var name
	import Content from './pages/test.svelte'
	import Navigation from './pages/navigation.svelte'
</script>
<div class="app dark">
	<Navigation theme={"light"}/>
	<Content/>
</div>

<style>
	.app {
		font-family: Montserrat, "Segoe UI", sans-serif;
		width: 100%;
		height: 100%;
		display:flex;
		flex-direction: column;
	}
</style>