<script lang="ts">
	import Header from '$lib/components/Header.svelte';
	import Hero from '$lib/components/Hero.svelte';
	import IssuersSection from '$lib/components/IssuersSection.svelte';
	import FeaturesGrid from '$lib/components/FeaturesGrid.svelte';
	import InvestorsSection from '$lib/components/InvestorsSection.svelte';
	import TokenizedFunds from '$lib/components/TokenizedFunds.svelte';
	import TokenizedEquities from '$lib/components/TokenizedEquities.svelte';
	import NewsSection from '$lib/components/NewsSection.svelte';
	import CTASection from '$lib/components/CTASection.svelte';
	import Footer from '$lib/components/Footer.svelte';
</script>

<Header />

<main>
	<Hero />
	<IssuersSection />
	<FeaturesGrid />
	<InvestorsSection />
	<TokenizedFunds />
	<TokenizedEquities />
	<NewsSection />
	<CTASection />
</main>

<Footer />

