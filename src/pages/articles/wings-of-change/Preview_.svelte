<script>
  import thumb from './_images/thumb.png';

  export let preview;
</script>

<style>
  img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
</style>

{#if preview}
  <img src={thumb} alt="Wood Thrush Population Map">
{/if}

