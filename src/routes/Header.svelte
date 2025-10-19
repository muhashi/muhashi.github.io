<script>
  import MuhashiTitle from "./MuhashiTitle.svelte";
</script>

<div id="container">
  <div id="header">
    <MuhashiTitle />
  </div>
</div>

<style>
  #container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    width: 100%;
    align-items: center;
  }

  #header {
    width: 100%;
    text-align: center;
    user-select: none;
  }
</style>
