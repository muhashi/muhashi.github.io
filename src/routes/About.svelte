<script lang="ts">
  import Email from "./Email.svelte";
</script>

<div class="about">
  <h3>about me :&rpar;</h3>
  <p>hellooo</p>
  <p>
    I like to make small games like <a href="https://geodle.me">Geodle</a>
  </p>
  <p>
    You can <Email domain="muhashi" name="hello" tld="com"
      >email me here</Email
    >, or find me on <a href="https://github.com/muhashi">Github</a>
  </p>
  <p>you can also leave a message in <a href="https://muhashi.atabook.org/">my guestbook</a></p>
</div>

<style>
  .about {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    width: 80%;
  }

  p {
    margin: 0.5rem 0;
  }
</style>
