<script lang="ts">
  import Sidebar from '$lib/components/Sidebar.svelte';
  import Hero from '$lib/components/Hero.svelte';
  import YellowIcons from '$lib/components/YellowIcons.svelte';
  import LegacyComparison from '$lib/components/LegacyComparison.svelte';
  import AiFeature from '$lib/components/AiFeature.svelte';
  import FundingCards from '$lib/components/FundingCards.svelte';
  import TeamSection from '$lib/components/TeamSection.svelte';
  import Investors from '$lib/components/Investors.svelte';
  import Footer from '$lib/components/Footer.svelte';
</script>

<div class="flex min-h-screen bg-white font-sans">
  <Sidebar />
  
  <main class="flex-1 xl:pl-0 w-full">
    <Hero />
    <YellowIcons />
    <LegacyComparison />
    <AiFeature />
    <FundingCards />
    <TeamSection />
    <Investors />
    <Footer />
  </main>
</div>


