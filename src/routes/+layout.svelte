<script>
	import './layout.css'
    import Navbar from '$lib/navbar.svelte';
</script>

<div class="flex flex-col min-h-screen bg-black text-stone-200 overflow-x-hidden">
    <Navbar/>
    <slot />
</div>