<script lang="ts">
	// import { Button } from '$lib/components/ui/button';
	import * as Sidebar from '$lib/components/ui/sidebar/index.js';
	//
</script>

<div class="flex h-screen w-full flex-col items-center bg-gray-500 p-4 font-serif">
	<div class="flex w-full flex-row items-center justify-between rounded-sm bg-gray-400 shadow-lg">
		<Sidebar.Trigger class="align-left w-10" />

		<div
			class="inline-block bg-gradient-to-r from-blue-600 to-blue-300 bg-clip-text py-2 text-5xl font-bold text-transparent drop-shadow-[0_2.2px_1.2px_rgba(0,0,0,0.4)]"
		>
			Epubs.click
		</div>
		<div class="w-0"></div>
	</div>

	<h2 class="py-4 italic">Read and Modify EPUBs</h2>
	<h2>
		David Metcalfe (<a
			class="text-blue-600 underline visited:text-blue-700 hover:text-blue-800"
			href="mailto:crdjm1@gmail.com?subject=EpubHub">crdjm1@gmail.com</a
		>)
	</h2>

	<p class="pt-2">
		Epubs.click will provide various resources for reading and modifying EPUBs, initially:
	</p>
	<ul
		class="mt-2 list-inside list-disc rounded-lg border-2 border-solid border-gray-300 bg-gray-400 p-2"
	>
		<li class="pt-1"><b>EpubHub, an npm package for reading, analyzing, and modifying EPUBs</b></li>
		<li class="pt-1">
			<b>EpubHub-test, a test suite for EpubHub that may be used to build your own applications</b>
		</li>
		<li class="pt-1">EpubHub-cli, a command line interface for EpubHub</li>
		<li class="pt-1">EpubHub-gui, a desktop graphical user interface for EpubHub</li>
		<li class="pt-1">EpubHub-web (this site), a web application for EpubHub</li>
	</ul>

	<p class="pt-2">
		<b
			>EpubHub is available via npm today, and the source downloadable from <a
				target="_blank"
				class="text-blue-600 underline visited:text-blue-700 hover:text-blue-800"
				href="https://github.com/crdjm/epubhub">GitHub</a
			>. EpubHub-test is available via
			<a
				target="_blank"
				class="text-blue-600 underline visited:text-blue-700 hover:text-blue-800"
				href="https://github.com/crdjm/epubhub-test">GitHub</a
			>.</b
		>
	</p>
	<p class="pt-2">
		<i
			>Everything else is in development, at various stages of completion, and will be added when
			further along. Please contact me if you have any questions or would like access sooner.</i
		>
	</p>

	<p class="pt-4">
		EpubHub and the derived projects will utilise AI to improve the quality of the content when
		appropriate.
	</p>

	<p class="pt-2">
		All of the above is still <span class="italic">in development</span>. Please check back for
		updates, or contact me at
		<a
			class="text-blue-600 underline visited:text-blue-700 hover:text-blue-800"
			href="mailto:crdjm1@gmail.com?subject=EpubHub">crdjm1@gmail.com</a
		> if you have any questions.
	</p>
</div>

<!-- <Button variant="outline">Button</Button> -->
