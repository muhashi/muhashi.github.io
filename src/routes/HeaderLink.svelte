<script lang="ts">
  export let href: string;
  export let text: string;
  export let selected: boolean = false;
</script>

{#if selected}
  <p>
    {text}
  </p>
{:else}
  <a {href}>
    {text}
  </a>
{/if}

<style>
  a, a:visited, a:hover, a:active {
    color: inherit;
  }
</style>