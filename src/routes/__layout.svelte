<script>
  import Nav from "$lib/Nav.svelte";
</script>

<div class="container">
  <Nav />
  <slot />
</div>

<style>
  .container {
    min-height: 100vh;
    background: lightgoldenrodyellow;
  }

  :global(h1) {
    margin: 0;
  }
</style>

