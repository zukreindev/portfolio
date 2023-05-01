<script>
	import Background from '../components/Background.svelte';
	import Main from '../components/Main.svelte';
</script>

<svelte:head>
	<title>Zukrein</title>
</svelte:head>

<main class="bg-black h-screen w-screen overflow-auto md:overflow-hidden">
	<img src="/eclipse.svg" class="absolute -left-32 -top-32 h-96 lg:h-fit" alt="" />
	<img src="/yellow_glossy.svg" class="absolute right-0 bottom-0 hidden lg:block" alt="" />
	<img src="/pillBlueGlossy.svg" class="fixed top-1/2 z-40 hidden lg:block" alt="" />
	<Main />
</main>
