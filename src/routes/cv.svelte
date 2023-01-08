<svelte:head>
    <title>thorcc - cv</title>
</svelte:head>

<script>
    let hidden = true;
    const hiddenstring = {
      text1: "thorchrcow",
      text2: "gmail.com",
    };
  
    const handleMailClick = () => {
      if (hidden) {
            hidden = false
          }
      }
</script>
  

<h2 id="title">CV</h2>

  <main>
    <div id="info">
      <h2>Thor Christian Coward</h2>
      <ul>
        <li id="mail" on:click={handleMailClick}>
            {#if hidden}
              Se epost
            {:else}
              <a href="mailto:{hiddenstring.text1}@{hiddenstring.text2}">{hiddenstring.text1}@{hiddenstring.text2}</a>
            {/if}
        </li>
      </ul>
    </div>
      
    <div>    
      <h3>Arbeid</h3>
      <ul>
        <li>Lærer på Sandvika videregående skole, underviser i IT1 og IT2</li>
      </ul>
  
      <h3>Utdanning</h3>
      <ul>
        <li>UiO: Faglig påfyll - 60 studiepoeng i informatikk</li>
        <li>UiO: Praktisk pedagogisk utdanning (PPU)</li>
        <li>NTNU: Produktutvikling og produksjon (2-årig master)</li>
        <li>HiOA: Maskiningeniør (bachelor)</li>
      </ul>
  
      <h3>IT-kompetanse</h3>
  
      <h4>Teknologier</h4>
      <ul>
        <li>Webutvikling - HTML, CSS, Javascript, Node, ReactJS, NextJS, Gatsby, Svelte, SvelteKit ++</li>
        <li>Databaser og CMS - SQL, Firebase, Sanity, Supabase</li>
        <li>Docker</li>
        <li>Ingeniørarbeid - KBE (AML), 3D-modellering, algoritmer og datastrukturer</li>
        <li>Multimedier - Photoshop, Illustrator, XD, Premiere Pro, Audition</li>
      </ul>
      <h4>Programmeringsspråk</h4>
      <ul>
        <li>Javascript</li>
        <li>Typescript</li>
        <li>Python</li>
        <li>Java</li>
        <li>Lisp (<a target="_blank" href="https://www.technosoft.com/application-software/adaptive-modeling-language/">AML</a>)</li>
      </ul>
  
  
      <h3>Diverse</h3>
      <ul>
        <li><a target="_blank" href="https://github.com/thorcc">github.com/thorcc</a></li>
        
        <li>
          <a target="_blank" href="cv.pdf">cv.pdf</a>
        </li>
      </ul>
    </div>
  
  </main>
  

  <style>
    #title{
        font-family: 'Krona One', sans-serif;
        font-size: 1.5rem;
    }
    main{
        background-color: #daeaf6;
        padding: 0.5rem;
        margin: 1rem 0;
        border-radius: 5px;
        box-shadow: 5px 5px rgba(0, 0, 0, 0.2);
    }

    #mail{
      text-decoration: underline;
      cursor: pointer;
    }
    a{
      color: blue;
    }
</style>
  