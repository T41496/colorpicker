<script>
  import ColorPicker from "./lib/ColorPicker.svelte";
</script>

<main>
  <div class="banner">
    <a href="https://svelte.dev" target="_blank" rel="noreferrer">
      <img src="/svelte.svg" class="logo" alt="Svelte Logo" />
    </a>
    <h1>ColorPicker</h1>
  </div>
  <ColorPicker />
</main>

<style>
  main {
    max-width: 576px;
    margin: 0 auto;
    padding: 2rem;
    border-radius: 5px;
    border: 1px #ff3e00aa solid;
    overflow-y: auto;
    max-height: calc(100vh - 4rem);
  }
  .logo {
    height: 6em;
    will-change: filter;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .banner {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
</style>
