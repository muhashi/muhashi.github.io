<script>
  import Header from "./Header.svelte";
  import About from "./About.svelte";
  import Projects from "./projects/Projects.svelte";

  console.log("🔑 STINGRAY");
</script>

<div>
  <Header />
  <About />
  <Projects />
  <footer>
    <p id="footer-text">
      What are you looking down here for 🤔 Some kinda secret?
    </p>
    <p id="footer-text" style="color: lightgray; font-size: 1rem;">
      19 5 3 18 5 20 0 4 15 20 0 13 21 8 1 19 8 9 0 4 15 20 0 3 15 13
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
    font-size: 1.1rem;
    color: gray;
    text-align: center;
    margin: 1rem 2rem;
  }
</style>
