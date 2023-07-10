<script>
    import Header from '../Header.svelte';
    import Projects from './Projects.svelte';
</script>

<div class="container">
    <Header />
    <Projects />
</div>

<style>
    .container {
        display: flex;
        flex-direction: column;
        justify-content: flex-start;
        align-items: center;
    }
</style>
