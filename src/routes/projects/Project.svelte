<script lang="ts">
  export let href: string;
  export let name: string;
  export let description: string;
  export let imageFile: string = "";
  export let imageAlt: string = "";
</script>

<div>
  <h3>
    <a href={href}>{name}</a>
  </h3>
  <div id="project-info">
    {#if imageFile}
      <div id="image-container">
        <img src={imageFile} alt={imageAlt} />
      </div>
    {/if}
    <div id="project-description">
      <p>
        {description}
      </p>
    </div>
  </div>
</div>

<style>
  #image-container {
    width: 50%;
  }

  img {
    margin: auto 0;
    max-width: 100%;
    max-height: 20rem;
  }

  #project-description {
    width: 50%;
    flex-grow: 1;
  }

  p {
    margin-top: 0;
  }

  #project-info {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: flex-start;
    gap: 2rem;
  }

  @media (max-width: 500px) {
    #image-container {
      width: 100%;
    }

    #project-description {
      width: 100%;
    }

    img {
      max-width: 80vw;
    }

    #project-info {
      flex-direction: column;
    }
  }
</style>
