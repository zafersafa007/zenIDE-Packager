<script>
  import Section from './Section.svelte';
  const color = '#b117f8';
</script>

<style>
  .badge {
    background-color: #b117f8;
    border-bottom: 2px solid #6f0073;
    color: white;
    padding: 2px 5px;
    border-radius: 4px;
  }
</style>

<Section accent={color}>
  <div>
    <p><span class="badge">New!</span> The packager should finally work now, and we even took the time to rebrand it!</p>
  </div>
</Section>
