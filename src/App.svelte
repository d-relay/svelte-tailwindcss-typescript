<script lang="ts">
  export let name: string;
</script>

<style>
  main {
    @apply h-screen bg-white flex justify-center items-center;
  }
</style>

<main>
  <h1 class="font-semibold text-5xl text-orange-500">Svelte + {name}</h1>
</main>
