<script>
  import Project from "./Project.svelte";
</script>

<div class="sections">
  <div class="projects">
    <h3>games and stuff</h3>

    <hr />

    <Project
      name="Geodle"
      href="https://geodle.me"
      description="A Wordle-like game that tests your knowledge of country demographics by having you guess the country based on demographics like continent, population and average temperature."
      imageFile="geodle.png"
      imageAlt="Screenshot of Geodle"
    />

    <Project
      name="AITA Guesser"
      href="https://muhashi.com/aita-guesser/"
      description="Guess the verdict for over 1000 popular r/AmItheAsshole Reddit posts."
      imageFile="aita.png"
      imageAlt="Screenshot of AITA Guesser"
    />

    <Project
      name="Coindle"
      href="https://muhashi.com/coindle/"
      description="Call as many coin flips correctly in a row as you can! Only 1 attempt per day."
      imageFile="coindle.png"
      imageAlt="Screenshot of Coindle"
    />

    <Project
      name="Seadle"
      href="https://seadle.muhashi.com/"
      description="Guess the sea of the day! Learn about the world's seas and use directions and distance to narrow down the secret sea."
      imageFile="seadle.png"
      imageAlt="Screenshot of Seadle"
    />

    <Project
      name="What could you buy instead of a house in Australia?"
      href="https://housing.muhashi.com/"
      description="The average Australian home costs over $1 million. What could you be getting instead?"
      imageFile="housing.png"
      imageAlt="Screenshot of housing.muhashi.com"
    />

    <Project
      name="FakeNewsdle"
      href="https://muhashi.com/fakenewsdle/"
      description="Guess whether an absurd sounding headline is made up or a real news article! "
      imageFile="fakenewsdle.png"
      imageAlt="Screenshot of FakeNewsdle"
    />

    <Project
      name="Health Star Rating Calculator"
      href="https://muhashi.com/health-star-rating-web/"
      description="Calculate and explain the Australian/New Zealand Health Star Rating of foods."
      imageFile="health-star-rating-calculator.png"
      imageAlt="Screenshot of it's raining somewhere else"
    />
  </div>

  <!-- <div class="projects">
    <h3>for developers!</h3>

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

    <Project
      name="arpansa-uv-api"
      href="https://github.com/muhashi/arpansa-uv-api"
      description="An npm module for retrieving UV index data from the ARPANSA for multiple locations in Australia and Antarctica"
    />

    <Project
      name="sbs-on-demand-scraper"
      href="https://github.com/muhashi/sbs-on-demand-scraper"
      description="A Python command line tool to download the list of movies and TV shows currently available on SBS On Demand"
    />
  </div> -->
</div>

<style>
  .projects {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    width: 100%;
  }

  .sections {
    width: 80%;
    margin-top: 2rem;
  }

  hr {
    width: 100%;
  }

</style>
