<script>
   // export let titulo = "Menu";
   let { titulo, children } = $props();
</script>

<div class="
   flex
   flex-col
   gap-3
">
   <span class="
      text-sm
      font-bold
      text-zinc-500
   ">
      {titulo}
   </span>
   <ul class="flex flex-col">
      {@render children()}
   </ul>
</div>