<script>
  import Project from "./Project.svelte";
</script>

<div class="sections">
  <h2>some stuff i made :&rpar;</h2>
  <div class="projects">
    <h3>you can try these now!</h3>

    <hr />

    <Project
      name="Geodle"
      href="https://geodle.me"
      description="A Wordle-like game that tests your knowledge of country demographics by having you guess the country based on demographics like continent, population and average temperature"
      imageFile="geodle.jpg"
      imageAlt="Screenshot of Geodle"
    />

    <hr />

    <Project
      name="it's raining somewhere else"
      href="https://itsrainingsomewhereelse.com"
      description="A dumb little website that shows you a city where it's currently raining"
      imageFile="its-raining-somewhere-else.png"
      imageAlt="Screenshot of it's raining somewhere else"
    />

    <hr />
  </div>

  <div class="projects">
    <h3>you can use these in your own projects!</h3>

    <hr />

    <Project
      name="realestate.com.au Node.js API"
      href="https://github.com/muhashi/realestate.com.au"
      description="A Node.js API for realestate.com.au that allows you to search for properties and get their information"
    />

    <hr />

    <Project
      name="Calculate the ANZ Health Star Rating of Food in Node.js"
      href="https://github.com/muhashi/health-star-rating"
      description="An npm module for calculating the ANZ Health Star Rating of foods, which I made with the intent to use in a project that I never ended up finishing"
    />

    <hr />
  </div>
</div>

<style>
  .projects {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    width: 100%;
    margin-top: 5rem;
  }

  .sections {
    width: 80%;
  }

  hr {
    width: 100%;
  }
</style>
