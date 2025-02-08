<script>
	import Block from '$lib/components/Block.svelte';
	import PaperIcon from 'virtual:icons/mingcute/pdf-line';
	import GithubIcon from 'virtual:icons/mdi/github';
	import ArxivIcon from 'virtual:icons/simple-icons/arxiv';
	import Person from '$lib/components/Person.svelte';
	import NavLink from '$lib/components/NavLink.svelte';
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
			<div class="text-md mt-4 text-gray-800">July 19th, 2025</div>
		</div>
	</div>
	<!-- <div class="w-full border-b border-gray-500"></div> -->
	<div
		class="bg-opacity-70 sticky top-0 z-10 flex w-full items-start justify-center bg-gray-100 backdrop-blur-md"
	>
		<div class="mx-8 w-full max-w-2xl select-none">
			<div class="my-4 flex flex-row items-center justify-start font-mono text-sm md:text-base">
				<NavLink href="#schedule">SCHEDULE</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<NavLink href="#speakers">SPEAKERS</NavLink>
				<div class="mx-2 text-gray-400">/</div>
				<NavLink href="#organizers">ORGANIZERS</NavLink>
			</div>
		</div>
	</div>
	<div class="flex w-full items-end justify-center font-serif">
		<div class="mx-8 w-full max-w-2xl text-black">
			<div class="mt-8 mb-8 flex text-sm md:text-base"></div>
		</div>
	</div>
	<Block padding="pb-8" class="md:text-justify">
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
	<Block padding="pb-4">
		<h1 class="mb-4 text-2xl font-bold" id="speakers">Speakers</h1>
	</Block>
	<Block size="max-w-4xl">
		<div class="flex flex-col items-center justify-center">
			<div class="flex flex-wrap justify-center">
				<Person
					name="Zora Wang"
					affiliation="CMU"
					link="https://zorazrw.github.io/"
					image="https://zorazrw.github.io/images/profile.jpg"
				></Person>
				<Person
					name="Wenhao Yu"
					affiliation="DeepMind"
					link="https://wenhaoyu.weebly.com/"
					image="https://wenhaoyu.weebly.com/uploads/1/4/2/4/14248981/published/img-1723.jpg?1687933779"
				></Person>
				<Person
					name="Sheila McIlraith"
					affiliation="University of Toronto"
					link="https://www.cs.toronto.edu/~sheila/"
					image="https://www.cs.toronto.edu/~sheila/img/McIlraith2-lowres.jpg"
				></Person>
				<Person
					name="Dale Schuurmans"
					affiliation="DeepMind / Alberta"
					link="https://webdocs.cs.ualberta.ca/~dale/"
					image="https://storage.googleapis.com/gweb-research2023-media/pubtools/4145.png"
				></Person>
				<Person
					name="Kevin Ellis"
					affiliation="Cornell"
					link="https://www.cs.cornell.edu/~ellisk/"
					image="data:image/jpeg;base64,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"
				></Person>
			</div>
		</div>
	</Block>
	<!-- <Block>
		<h1 class="mb-4 text-2xl font-bold" id="panelists">Panelists</h1>
	</Block> -->
	<Block>
		<h1 class="mb-4 text-2xl font-bold" id="organizers">Organizers</h1>
	</Block>
	<Block size="max-w-4xl">
		<div class="flex flex-col items-center justify-center">
			<div class="flex flex-wrap justify-center">
				<Person
					name="Shao-Hua Sun"
					affiliation="National Taiwan University"
					link="https://shaohua0116.github.io/"
					image="https://shaohua0116.github.io/images/profile.jpg"
				></Person>
				<Person
					name="Levi Lelis"
					affiliation="University of Alberta"
					link="https://webdocs.cs.ualberta.ca/~santanad/"
					image="https://webdocs.cs.ualberta.ca/~santanad/img/levi_amii.jpg"
				></Person>
				<Person
					name="Xinyun Chen"
					affiliation="DeepMind"
					link="https://jungyhuk.github.io/"
					image="https://jungyhuk.github.io/imgs/Xinyun.jpg"
				></Person>
				<Person
					name="Shreyas Kapur"
					affiliation="UC Berkeley"
					link="https://shreyaskapur.com/"
					image="./imgs/shreyas.jpg"
				></Person>
				<Person
					name="Jiayuan Mao"
					affiliation="MIT"
					link="https://jiayuanm.com/"
					image="https://jiayuanm.com/static/img/avatar24.jpg"
				></Person>
				<Person
					name="Ching-An Cheng"
					affiliation="Microsoft Research"
					link="https://www.chinganc.com/"
					image="https://www.chinganc.com/static/images/ching-an-cheng.jpg"
				></Person>
				<Person
					name="Anqi Li"
					affiliation="NVIDIA"
					link="https://anqili.github.io/"
					image="https://anqili.github.io/theme/images/anqi_li.jpg"
				></Person>
				<Person
					name="Kuang-Huei Lee"
					affiliation="DeepMind"
					link="https://kuanghuei.github.io/"
					image="https://kuanghuei.github.io/docs/images/profile.jpg"
				></Person>
				<Person
					name="Leslie Kaelbling"
					affiliation="MIT"
					link="https://people.csail.mit.edu/lpk/"
					image="https://siebelschool.illinois.edu/_sitemanager/viewphoto.aspx?id=10406&s=300"
				></Person>
			</div>
		</div>
	</Block>

	<div class="mt-8 flex w-full justify-center bg-gray-100 pt-4 font-sans">
		<div class="mx-8 w-full max-w-3xl">
			<div class="flex w-full flex-col items-center justify-start">
				<div class="mt-4 mb-8 text-2xl text-gray-500">
					<a
						href="https://github.com/pr4al-workshop/pr4al-workshop.github.io"
						target="_blank"
						rel="noreferrer"
						class="mr-2"
					>
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
				>
				and is based on the
				<a class="underline" href="https://leela-interp.github.io/" target="_blank" rel="noreferrer"
					>Leela Interp</a
				> project. That means you're free to borrow the source code of this website with attribution.
			</div>
		</div>
	</div>
</div>
