<script>
	import Navbar from '../components/Main/Navbar.svelte';
</script>

<main class="w-full h-full flex flex-col justify-center items-center">
	<div
		class="bg-gradient-to-br from-[#FFFFFF1A] to-[#FFFFFF0A] lg:h-fit h-full w-full lg:w-fit lg:px-20 lg:py-10 flex flex-col items-center justify-center rounded-lg border-[0.5px] border-[#ffffff5d] backdrop-blur-xl relative"
	>
		<img src="/whiteMatte.svg" class="absolute -top-2 -right-5 hidden lg:block" alt="" />
		<img src="/orangeGlossy.svg" class="absolute -bottom-12 right-1/3 hidden lg:block" alt="" />

		<div class="flex flex-col-reverse md:flex-row justify-center items-center">
			<div class="md:pr-8 flex flex-col items-start mx-10">
				<h1 class="font-bold text-2xl lg:text-4xl text-[#f9fafbec]">
					Hello! I am <span
						class="font-extrabold text-transparent text-3xl lg:text-5xl bg-clip-text bg-gradient-to-r from-[#F59E0B] to-[#EF4444]"
						>ZUKREIN</span
					>
				</h1>
				<p class="text-sm w-full lg:w-[500px] text-white py-5 mb-3">
					I am a UI designer and web developer who is passionate about creating beautiful and
					functional websites. With years of experience in the industry, I have developed a keen eye
					for design and a deep understanding of what it takes to create a successful online
					presence.
				</p>
				<a href="https://github.com/zukrein00" target="_blank" class="portfolioButton"
					>Go to Github</a
				>
			</div>
			<img src="/mainSection.png" class=" w-64 lg:w-96" alt="" />
		</div>
	</div>
</main>
