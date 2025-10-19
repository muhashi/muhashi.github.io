<script>
  import Header from "./Header.svelte";
  import About from "./About.svelte";
  import Projects from "./projects/Projects.svelte";
</script>

<div>
  <Header />
  <About />
  <Projects />
</div>

<style>
  div {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    width: 100%;
  }
</style>
