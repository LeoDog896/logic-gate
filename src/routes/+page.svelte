<script lang="ts">
  import { Node, Svelvet } from 'svelvet';

  let width: number;
  let height: number;
</script>

<svelte:window bind:innerWidth={width} bind:innerHeight={height}></svelte:window>

<Svelvet {width} {height} TD minimap controls>
  <Node />
  <Node label="Default Node" />
</Svelvet>
