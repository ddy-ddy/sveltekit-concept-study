<script>
  import Title from "../lib/title.svelte";
  import "../styles/global.css";
</script>

<header>
  <Title title="ddy-ddy sveltekit study" />
</header>

<main>
  <!-- page content -->
  <slot />
</main>

<footer>
  <p>Copyright 2022 ddy-ddy sveltekit study</p>
</footer>

<style>
  header {
    display: flex;
    justify-content: center;
  }
  main {
    max-width: 960px;
    margin: 20px auto;
  }
  footer {
    text-align: center;
  }
</style>
