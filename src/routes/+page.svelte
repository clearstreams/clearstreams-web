<script>
  import Navbar from "../components/Navbar.svelte";
  import Footer from "../components/Footer.svelte";
  import Hero from "../components/Hero.svelte";
  import IndexCard from "../components/IndexCard.svelte";
  import ReportsCard from "../components/ReportsCard.svelte";
</script>

<Navbar/>

<Hero />
<ReportsCard />
<div class="container mx-auto px-4 md:px-12">
  <div class="flex flex-wrap -mx-1 lg:-mx-4 justify-center">
    <IndexCard />
  </div>
</div>


<Footer />

<style lang="postcss">
  :global(html) {
    background-color: theme(colors.gray.100);
  }
</style>