<script lang="ts">
  import Link from "./Link.svelte";
  import Email from "./Email.svelte";
</script>

<div class="about">
  <h3>about me :&rpar;</h3>
  <p>hellooo, I'm muhashi</p>
  <p>
    If you're here from <Link href="https://geodle.me" text="Geodle" />, check
    out <Link href="/projects" text="my other stuff" />!
  </p>
  <p>
    You can <Email domain="gmail" name="muhamedoes+muhashi" tld="com"
      >email me here</Email
    >, or find me on <Link href="https://github.com/muhashi" text="Github" />
  </p>
  <p>that is all</p>
</div>

<style>
  .about {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    width: 80%;
  }
</style>
