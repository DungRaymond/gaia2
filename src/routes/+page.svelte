<script>
  import { Grid } from '@svelteuidev/core';
  import Fa from 'svelte-fa/src/fa.svelte';
  import { faPhone } from '@fortawesome/free-solid-svg-icons'
</script>

<div id="navbar">
  <Grid>
    <Grid.Col span={1} class="navbar-ele">
      <Fa icon={faPhone} size={'0.8x'} />
      0364343213
    </Grid.Col>
  </Grid>
</div>

<style>
  .navbar-ele {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }
</style>