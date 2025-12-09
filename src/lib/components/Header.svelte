<script lang="ts">
	import { onMount } from 'svelte';

	let isScrolled = false;

	onMount(() => {
		const handleScroll = () => {
			isScrolled = window.scrollY > 20;
		};
		window.addEventListener('scroll', handleScroll);
		return () => window.removeEventListener('scroll', handleScroll);
	});
</script>

<header class="fixed top-0 left-0 w-full z-50 transition-all duration-300 {isScrolled ? 'bg-dark-black/80 backdrop-blur-md py-4' : 'bg-transparent py-6'}">
	<div class="max-w-[1400px] mx-auto px-6 flex items-center justify-between text-white">
		<!-- Logo -->
		<a href="/" class="flex items-center gap-2 group">
			<div class="w-8 h-8 bg-white rounded-full flex items-center justify-center text-black font-bold text-lg">
				<svg width="16" height="16" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="transform rotate-45">
					<path d="M12 2L2 12L12 22L22 12L12 2Z" fill="currentColor"/>
				</svg>
			</div>
			<span class="font-medium text-lg tracking-tight">Superstate</span>
		</a>

		<!-- Nav -->
		<nav class="hidden md:flex items-center gap-8 text-sm font-medium text-gray-300">
			<a href="#issuers" class="hover:text-white transition-colors">Issuers</a>
			<a href="#investors" class="hover:text-white transition-colors">Investors</a>
			<button class="flex items-center gap-1 hover:text-white transition-colors group">
				Assets
				<svg class="w-4 h-4 text-gray-500 group-hover:text-white transition-colors" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
			</button>
			<button class="flex items-center gap-1 hover:text-white transition-colors group">
				About
				<svg class="w-4 h-4 text-gray-500 group-hover:text-white transition-colors" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
			</button>
		</nav>

		<!-- Actions -->
		<div class="flex items-center gap-4">
			<a href="/login" class="text-sm font-medium px-5 py-2 rounded-full border border-gray-600 hover:border-white transition-colors">
				Sign In
			</a>
			<a href="/register" class="text-sm font-medium px-5 py-2 rounded-full bg-white text-black hover:bg-gray-200 transition-colors">
				Register
			</a>
		</div>
	</div>
</header>
