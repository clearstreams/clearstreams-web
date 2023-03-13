<script>
  import Navbar from "../components/Navbar.svelte";
  import Footer from "../components/Footer.svelte";
  import Hero from "../components/Hero.svelte";
</script>

<Navbar/>
<div>
  <Hero />
  <p>Dev Branch Test</p>
</div>
<Footer />

<style lang="postcss">
  :global(html) {
    background-color: theme(colors.gray.100);
  }
</style>