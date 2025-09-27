<script lang="ts">
  import Email from "./Email.svelte";
</script>

<div class="about">
  <h3>about me :&rpar;</h3>
  <p>hellooo, I'm muhashi</p>
  <p>
    I developed <a href="https://geodle.me">Geodle</a>, check
    out <a href="/projects">my other stuff</a>!
  </p>
  <p>
    You can <Email domain="muhashi" name="hello" tld="com"
      >email me here</Email
    >, or find me on <a href="https://github.com/muhashi">Github</a>
  </p>
  <p>you can leave a message in in <a href="https://muhashi.atabook.org/">my guestbook</a> :&rpar;</p>
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
