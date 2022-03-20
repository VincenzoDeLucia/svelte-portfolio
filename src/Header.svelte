<script>
  import Navigation from "./Navigation.svelte";
</script>

<header>
  <div class="logo">
    <img src="" alt="" />
  </div>

  <Navigation />
</header>

<style>
  header {
    display: flex;
    justify-content: space-between;
    padding: 1em;
  }

  .logo {
    max-width: 150px;
  }
</style>
