<script lang="ts">
  import Header from "$lib/components/Header.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import BentoGrid from "$lib/components/BentoGrid.svelte";
  import FeatureStablecoins from "$lib/components/FeatureStablecoins.svelte";
  import FeatureIcons from "$lib/components/FeatureIcons.svelte";
  import FeatureSecurity from "$lib/components/FeatureSecurity.svelte";
  import SecurityGrid from "$lib/components/SecurityGrid.svelte";
  import FooterCTA from "$lib/components/FooterCTA.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<div class="min-h-screen bg-white font-sans text-gray-900 selection:bg-gray-900 selection:text-white">
  <Header />
  <main>
    <Hero />
    <BentoGrid />
    <FeatureStablecoins />
    <FeatureIcons />
    <FeatureSecurity />
    <SecurityGrid />
    <FooterCTA />
  </main>
  <Footer />
</div>

