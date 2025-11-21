<script>
  import Header from "./Header.svelte";
  import About from "./About.svelte";
  import Projects from "./projects/Projects.svelte";
</script>

<div>
  <Header />
  <About />
  <Projects />
  <footer>
    <p id="footer-text">
      What are you looking down here for 🤔 What are you trying to find?
    </p>
  </footer>
</div>

<style>
  div {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: center;
    width: 100%;
  }

  #footer-text {
    font-size: medium;
    color: gray;
  }
</style>
