<script lang="ts">
	import '../styles/global.scss';
	import '../styles/variables.scss';
	import '../styles/fonts.scss';

	import '../app.css';

	let { children } = $props();
</script>

{@render children()}

<style lang="scss">
	@use '../styles/variables.scss';
	@use '../styles/fonts.scss';
</style>
