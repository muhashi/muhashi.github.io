<script>
  import { page } from "$app/stores";
  import HeaderLink from "./HeaderLink.svelte";
  import MuhashiTitle from "./MuhashiTitle.svelte";
</script>

<div id="container">
  <div id="header">
    <MuhashiTitle />
  </div>
  <nav id="links">
    <HeaderLink href="/" text="about" selected={$page.url.pathname === "/"} />
    <HeaderLink
      href="/projects"
      text="projects"
      selected={$page.url.pathname === "/projects"}
    />
  </nav>
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
    width: 50%;
    text-align: center;
    user-select: none;
  }

  #links {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    gap: 2rem;
    width: 50%;
  }

  @media (max-width: 500px) {
    #container {
      flex-direction: column;
      width: 100%;
    }

    #header {
      width: 100%;
    }

    #links {
      width: 100%;
      justify-content: space-evenly;
    }
  }
</style>
