<script lang="ts">
	import { Menu, X } from 'lucide-svelte';
    import { onMount } from 'svelte';

	let isMenuOpen = false;
    let isScrolled = false;

    function toggleMenu() {
        isMenuOpen = !isMenuOpen;
    }

    onMount(() => {
        const handleScroll = () => {
            isScrolled = window.scrollY > 20;
        };
        window.addEventListener('scroll', handleScroll);
        return () => window.removeEventListener('scroll', handleScroll);
    });
</script>

<nav class="fixed top-0 left-0 w-full z-50 transition-all duration-300 {isScrolled ? 'bg-black/80 backdrop-blur-md border-b border-white/10' : 'bg-transparent'} text-white">
	<div class="max-w-[1400px] mx-auto px-6 h-20 flex items-center justify-between">
		<!-- Logo -->
		<a href="/" class="text-xl font-sans tracking-tight font-semibold">DiligenceSquared</a>

		<!-- Desktop Links -->
		<div class="hidden lg:flex items-center gap-8 text-sm font-medium text-gray-300">
			<a href="#platform" class="hover:text-white transition-colors">Platform</a>
			<a href="#how-it-works" class="hover:text-white transition-colors">How It Works</a>
			<a href="#testimonials" class="hover:text-white transition-colors">Case Studies</a>
			<a href="#about" class="hover:text-white transition-colors">About</a>
		</div>

		<!-- Right Actions -->
		<div class="hidden lg:flex items-center gap-6">
			<a href="#contact" class="bg-primary-600 hover:bg-primary-700 text-white px-5 py-2.5 rounded-full text-sm font-medium transition-colors">
				Get Started
			</a>
		</div>

		<!-- Mobile Menu Button -->
		<button class="lg:hidden text-white" onclick={toggleMenu}>
			{#if isMenuOpen}
				<X size={24} />
			{:else}
				<Menu size={24} />
			{/if}
		</button>
	</div>

	<!-- Mobile Menu -->
	{#if isMenuOpen}
		<div class="lg:hidden bg-black absolute top-20 left-0 w-full h-[calc(100vh-80px)] p-6 flex flex-col gap-6 overflow-y-auto border-t border-white/10">
			<a href="#platform" class="text-lg font-medium text-gray-300 hover:text-white">Platform</a>
			<a href="#how-it-works" class="text-lg font-medium text-gray-300 hover:text-white">How It Works</a>
			<a href="#testimonials" class="text-lg font-medium text-gray-300 hover:text-white">Case Studies</a>
			<a href="#about" class="text-lg font-medium text-gray-300 hover:text-white">About</a>
			<div class="h-px bg-white/10 my-2"></div>
			<a href="#contact" class="bg-primary-600 text-white px-5 py-3 rounded-full text-center font-medium">
				Get Started
			</a>
		</div>
	{/if}
</nav>
