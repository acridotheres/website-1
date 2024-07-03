<script lang="ts">
	import '../styles/global.scss';
</script>

<div class="bg-black h-12 w-full"></div>

<nav class="fixed top-0 left-0 backdrop-blur-lg w-full h-12 border-b border-b-neutral-800 flex text-white items-center">
	<a href="/" class="flex p-1 items-center w-fit">
		<img src="/logo.png" alt="Acridotheres logo" class="h-10 mr-2">
		<h1 class="text-bold text-2xl">Acridotheres</h1>
	</a>
	<div class="flex flex-grow items-center justify-end h-full p-2 px-3">
		<a class="bg-white text-black h-full leading-6 p-1 px-2 rounded-md" href="/download">Download</a>
	</div>
</nav>

<main class="bg-black text-white w-full min-h-[calc(100vh-3rem)]">
	<slot />
</main>

<footer>
	<p class="text-center text-white bg-black p-2">
		&copy; 2024 Leonard Lesinski and all Acridotheres contributors
	</p>
</footer>