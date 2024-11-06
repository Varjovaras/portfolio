<script lang="ts">
	import '../app.css';
	const { children } = $props();
	export const prerender = true;
</script>

<div class="flex flex-col justify-center">
{@render children()}
</div>
