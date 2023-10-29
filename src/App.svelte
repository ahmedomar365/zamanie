<script lang="ts">
  import Greet from './lib/Greet.svelte'
</script>

<main class="container">

  <div class="row">

      <img src="/logo/zamanie.png" class="logo svelte" alt="Svelte Logo" />
  </div>

  <p>
    Click on the Tauri, Vite, and Svelte logos to learn more.
  </p>

  <div class="row">
  </div>


</main>

<style>
  .logo.vite:hover {
    filter: drop-shadow(0 0 2em #747bff);
  }

  .logo.svelte:hover {
    filter: drop-shadow(0 0 2em #ff3e00);
  }
</style>