<script>
	import Navbar from '../components/Main/Navbar.svelte';
</script>

<main class="w-full h-full flex flex-col justify-center items-center">
	<div class="mainBackground relative">
		<img src="/whiteMatte.svg" class="absolute -top-2 -right-5" alt="" />
		<img src="/orangeGlossy.svg" class="absolute -bottom-12 right-1/3" alt="" />

		<div class="flex justify-center items-center">
			<div class="pr-8">
				<h1 class="font-bold text-4xl text-[#f9fafbec]">
					Hello! I am <span class="mainName">ZUKREIN</span>
				</h1>
				<p class="text-sm w-[500px] text-white py-5 mb-3">
					I am a UI designer and web developer who is passionate about creating beautiful and
					functional websites. With years of experience in the industry, I have developed a keen eye
					for design and a deep understanding of what it takes to create a successful online
					presence.
				</p>
				<a href="https://github.com/zukrein00" target="_blank" class="portfolioButton ">Go to Github</a>
			</div>
			<img src="/mainSection.png" class=" w-96" alt="" />
		</div>
	</div>
</main>
