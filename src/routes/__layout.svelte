<script>
    import { page } from '$app/stores';
    let path;

    $: path = $page.url.pathname;
</script>

<header>
    <div class="name">
        <a href="/">
            <h1>
                Thor Christian Coward
            </h1>
        </a>
    </div>
    <div class="info">
        <h2>Utvikler, lektor og sivilingeniør</h2>
    </div>
    
    
    
    <img id="mainImage" src="/bilde.jpg" alt="Thor Christian sitter på huk ved siden av en tøff bil"/>
    {#if path == "/"}
        <a id="navLink" href="/cv">Se CV</a>
    {:else}
        <a id="navLink" href="/">Se prosjekter</a>
    {/if}
</header>


<main>
    <slot />
</main>

<style>
    .name a, #name a *{
        font-family: 'Roboto', sans-serif;
        font-size: 0.7rem;
        color: black;
        text-decoration: none;
        text-transform: uppercase;
    }
    h2{
        font-family: 'Krona One', sans-serif;
        font-size: 1.5rem;
    }
    main, header{
        max-width: 600px;
        margin: auto;
    }
    #mainImage {
      display: block;
      width: 100%;
      height: 300px;
      object-fit: cover;
      object-position: center 40%;
      margin: 1rem auto;
      border-radius: 5px;
      box-shadow: 5px 5px rgba(0, 0, 0, 0.2);
    }
    a{
        color: black;
        font-family: 'Roboto', sans-serif;
    }
</style>