<script>
	import Block from '$lib/components/Block.svelte';
	import PaperIcon from 'virtual:icons/mingcute/pdf-line';
	import GithubIcon from 'virtual:icons/mdi/github';
	import ArxivIcon from 'virtual:icons/simple-icons/arxiv';
</script>

<svelte:head>
	<title>Programmatic Representations for Agent Learning Workshop at ICML 2025</title>
</svelte:head>

<div class="text-lg">
	<div class="flex w-full items-end justify-center font-serif">
		<div class="mx-8 w-full max-w-2xl pt-8 pb-12 text-black md:pt-28">
			<div class="mb-4 text-sm">
				<div class="inline-block rounded-md border border-black px-2 py-1 font-mono">
					ICML WORKSHOP
				</div>
			</div>
			<div class="inline-block text-4xl">Programmatic Representations for Agent Learning</div>
			<div class="text-md mt-4 text-gray-700">July 19th, 2025</div>
		</div>
	</div>
	<!-- <div class="w-full border-b border-gray-500"></div> -->
	<div
		class="bg-opacity-70 sticky top-0 z-10 flex w-full items-start justify-center bg-gray-100 backdrop-blur-md"
	>
		<div class="mx-8 w-full max-w-2xl select-none">
			<div class="my-4 flex flex-col text-sm md:text-base">
				<div class="mb-2 font-mono text-xs text-gray-400 uppercase">NAVIGATION</div>
				<div></div>
			</div>
		</div>
	</div>
	<div class="flex w-full items-end justify-center font-serif">
		<div class="mx-8 w-full max-w-2xl text-black">
			<div class="mt-8 mb-8 flex text-sm md:text-base"></div>
		</div>
	</div>
	<Block padding="pb-8">
		This workshop explores the emerging paradigm of using programmatic representations to enhance
		the interpretability, generalizability, efficiency, and scalability of frameworks for agent
		learning and decision-making. The goal of this workshop is to bring together the sequential
		decision- making community, which includes robot learning, robotics, reinforcement learning,
		imitation learning, planning, search, and optimal control, with the code generation and program
		synthesis communities to confront the challenges in agent and robot learning at scale and solve
		specific applications ranging from virtual agents to robotics.
	</Block>
	<Block>
		<h1 class="mb-4 text-2xl font-bold" id="schedule">Tentative Schedule</h1>
	</Block>
	<Block>
		<h1 class="mb-4 text-2xl font-bold" id="speakers">Speakers</h1>
	</Block>
	<Block>
		<h1 class="mb-4 text-2xl font-bold" id="panelists">Panelists</h1>
	</Block>
	<Block>
		<h1 class="mb-4 text-2xl font-bold" id="organizers">Organizers</h1>
	</Block>

	<div class="mt-8 flex w-full justify-center bg-gray-100 pt-4 font-sans">
		<div class="mx-8 w-full max-w-3xl">
			<div class="flex w-full flex-col items-center justify-start">
				<div class="mt-4 mb-8 text-2xl text-gray-500">
					<a href="#" target="_blank" rel="noreferrer" class="mr-2">
						<ArxivIcon class="inline-block hover:text-black" />
					</a>
					<a href="#" target="_blank" rel="noreferrer" class="mr-2">
						<GithubIcon class="inline-block hover:text-black" />
					</a>
				</div>
			</div>
			<div class="mb-24 text-sm text-gray-600">
				This website is licensed under a <a
					class="underline"
					href="http://creativecommons.org/licenses/by-sa/4.0/"
					target="_blank"
					rel="noreferrer">Creative Commons Attribution-ShareAlike 4.0 International License</a
				>. This means you are free to borrow the source code of this website, we just ask that you
				link back to this page in the footer.
			</div>
		</div>
	</div>
</div>
