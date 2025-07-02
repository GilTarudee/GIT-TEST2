<script lang="ts">
	export const prerender = true;
	import '../app.css';
	let { children } = $props();
</script>

<div class="m-4">
	{@render children()}
</div>
