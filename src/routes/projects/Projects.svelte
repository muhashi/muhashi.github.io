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
      description="A Wordle-like game that tests your knowledge of country demographics by having you guess the country based on demographics like continent, population and average temperature.<br><br>Made with TypeScript, React.js, and Material UI. "
      imageFile="geodle.jpg"
      imageAlt="Screenshot of Geodle"
    />
<!--
    <Project
      name="it's raining somewhere else"
      href="https://itsrainingsomewhereelse.com"
      description="A dumb little website that shows you a city where it's currently raining.<br><br>Made with TypeScript, React.js, Node.js, and Express.js."
      imageFile="its-raining-somewhere-else.png"
      imageAlt="Screenshot of it's raining somewhere else"
    />
-->
    <Project
      name="Health Star Rating Calculator"
      href="https://muhashi.com/health-star-rating-web/"
      description="Calculate and explain the Australian/New Zealand Health Star Rating of foods.<br><br>Made with Svelte."
      imageFile="health-star-rating-calculator.png"
      imageAlt="Screenshot of it's raining somewhere else"
    />
  </div>

  <div class="projects">
    <h3>you can use these in your own projects!</h3>

    <hr />

    <Project
      name="syllables"
      href="https://github.com/muhashi/syllables"
      description="An npm module that counts syllables in text using the CMU Pronouncing Dictionary"
    />

    <Project
      name="extractwords"
      href="https://github.com/muhashi/extractwords"
      description="A small npm module that extracts the words from text"
    />

    <Project
      name="generate-random-username"
      href="https://github.com/muhashi/generate-random-username"
      description="A tiny npm module to generate random usernames"
    />

    <Project
      name="rhymes-with"
      href="https://github.com/muhashi/rhymes-with"
      description="A small npm module that determines if two words rhyme, based on the CMU Pronouncing Dictionary"
    />

    <Project
      name="rhyming-part"
      href="https://github.com/muhashi/rhyming-part"
      description="An npm module to get the rhyming part of a word, which is useful to check if words rhyme or for grouping words that rhyme together."
    />

    <Project
      name="findahaiku"
      href="https://github.com/muhashi/findahaiku"
      description="An npm module to split up text into the lines of a haiku."
    />

    <Project
      name="health-star-rating"
      href="https://github.com/muhashi/health-star-rating"
      description="An npm module for calculating the ANZ Health Star Rating of foods, which is used in the above Health Star Rating Calculator site :)"
    />

    <Project
      name="exchange-rates-rba"
      href="https://github.com/muhashi/exchange-rates-rba"
      description="An npm module for retrieving daily foreign currency exchange rates for USD, EUR, and more from the Reserve Bank of Australia"
    />
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
