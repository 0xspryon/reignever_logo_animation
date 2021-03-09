<script lang="ts">
	import Nav from '../components/Nav.svelte';

	export let segment: string;
</script>

<style>
	main {
		height:100vh;
		width:100vw;
		padding:1em;
		display:flex;
		align-items:center;
		justify-content:center;
	}
</style>

<!-- <Nav {segment}/> -->

<main>
	<slot></slot>
</main>