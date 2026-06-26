<script>
   import Cabecalho from "./Cabecalho.svelte";
   import Rodape from "./Rodape.svelte";
   let { children } = $props();
</script>
<div class="flex flex-col min-h-screen bg-black text-white">
   <Cabecalho />
   <main class="flex-1">
      {@render children()}
      <!-- <slot></slot> -->
   </main>
   <Rodape />
</div>