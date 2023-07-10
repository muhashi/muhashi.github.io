<!-- thank you john https://github.com/rallisf1/svelte-hidden-email/blob/main/src/HiddenEmail.svelte -->

<script lang="ts">
    export let name: string;
    export let domain: string;
    export let tld: string;

    function handleMailLink(e: Event) {
        e.preventDefault();
        const el: EventTarget | null = e.target;

        if (el === null || !(el instanceof HTMLAnchorElement)) return;

        window.open('mailto:' + el.dataset.name + '@' + el.dataset.domain + '.' + el.dataset.tld);
    }
</script>

<!-- svelte-ignore a11y-invalid-attribute -->
<a href="#"
    data-tld={tld}
    data-domain={domain}
    data-name={name}
    on:click={handleMailLink}>
    <slot></slot>
</a>
