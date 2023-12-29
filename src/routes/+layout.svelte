<script lang="ts">
import Header from '$lib/Header.svelte';
</script>

<Header/>
<main>
  
  <slot></slot>
</main>

<style>
 main{

   padding: 0 5vw 3.375rem;
 }
</style>