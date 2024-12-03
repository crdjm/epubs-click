<script lang="ts">
	import '../app.css';
	import * as Sidebar from '$lib/components/ui/sidebar/index.js';
	import AppSidebar from '$lib/components/app-sidebar.svelte';

	let { children } = $props();
</script>

<Sidebar.Provider class="w-full bg-gray-200">
	<AppSidebar />
	<main>
		<!-- <Sidebar.Trigger /> -->
		{@render children?.()}
	</main>
</Sidebar.Provider>
