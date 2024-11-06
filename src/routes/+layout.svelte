<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<div class="flex flex-col justify-center ">
{@render children()}
</div>
