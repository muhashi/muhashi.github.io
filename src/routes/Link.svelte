<script lang="ts">
  export let href: string;
  export let text: string;
  export let selected: boolean = false;
  export let onClick: (e: Event) => void = () => {};
</script>

{#if selected}
  <p>
    {text}
  </p>
{:else}
  <a {href} on:click={onClick}>
    {text}
  </a>
{/if}
