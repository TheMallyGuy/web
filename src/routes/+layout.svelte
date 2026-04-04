<script>
	import './layout.css'
    import Navbar from '$lib/navbar.svelte';
    let { children } = $props();
</script>

<div class="flex flex-col min-h-screen bg-black text-stone-200 overflow-x-hidden">
    <Navbar/>
    {@render children?.()}
</div>