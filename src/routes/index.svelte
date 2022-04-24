<svelte:head>
    <title>thorcc</title>
</svelte:head>

<section class="projects">
    <h2>Prosjekter</h2>
    <div>
        <article>
            <h3>Portefølje for Roger Wagland</h3>
            <a target="_blank" href="https://wagland.art/">
                <p>wagland.art</p>
                <img src="wagland-500.jpg" alt="">
            </a>
            <p>Portefølje for billedkunsteneren Roger Wagland. Laget med React og Firebase.</p>
            <a target="_blank" href="https://github.com/thorcc/wagland-art-react">
                <p>Se koden på github</p>
            </a>
        </article>
        <article>
            <h3>Portefølje for Jonas Ropstad</h3>
            <a target="_blank" href="https://jonasropstad.netlify.com/">
                <p>jonasropstad.netlify.com</p>
                <img src="jonas-500.jpg" alt="">
            </a>
            <p>Portefølje for billedkunsteneren Jonas Ropstad. Laget med Gatsby og Contentful.</p>
            <a target="_blank" href="https://github.com/thorcc/jonas-portefolje">
                <p>Se koden på github</p>
            </a>
        </article>
        <article>
            <h3>Artistbildesøk</h3>
            <a target="_blank" href="https://artist-img.glitch.me/">
                <p>artist-img.glitch.me</p>
                <img src="artist-500.jpg" alt="">
            </a>
            <p>Veldig enkel søkemotor for artistbilder. Laget med HTML, CSS, Node og Spotifys API.</p>
            <a target="_blank" href="https://glitch.com/edit/#!/artist-img">
                <p>Se koden på glitch.com</p>
            </a>
        </article>
        <article>
            <h3>Sandvika.it</h3>
            <a target="_blank" href="https://sandvika.it/">
                <p>sandvika.it</p>
                <img src="sandvika-500.jpg" alt="">
            </a>
            <p>Digital lærebok for IT1. Laget med Markdown og Docsify.</p>
            <a target="_blank" href="https://github.com/sandvika-VGS/sandvika-VGS.github.io/">
                <p>Se koden på github</p>
            </a>
        </article>
        <article>
            <h3>Flask-VGS</h3>
            <a target="_blank" href="https://marketplace.visualstudio.com/items?itemName=thorcc.flask-vgs&ssr=false#review-details">
                <p>marketplace.visualstudio.com/flask-vgs</p>
                <img src="flask-vgs-500.jpg" alt="">
            </a>
            <p>Utvidelse til VS Code som lar brukere enkelt opprette Flask-prosjekter. Laget med Javascript.</p>
            <a target="_blank" href="https://github.com/thorcc/flask-vgs-vscode-extension">
                <p>Se koden på github</p>
            </a>
        </article>
        <article>
            <h3>Setify</h3>
            <a target="_blank" href="https://setify.netlify.app">
                <p>setify.netlify.app</p>
                <img src="setify-500.jpg" alt="">
            </a>
            <p>En webapp som lager Spotify-spillelister fra setlister. Laget med React, og API-er fra Spotify, Setlist.FM og Musicbrainz.</p>
            <a target="_blank" href="https://github.com/thorcc/flask-vgs-vscode-extension">
                <p>Se koden på github</p>
            </a>
        </article>
    </div>
</section>

<style>
    h2{
        font-family: 'Krona One', sans-serif;
        font-size: 1.5rem;
    }
    img{
        display: block;
        width: 100%;
        border-radius: 5px;
        box-shadow: 5px 5px rgba(0, 0, 0, 0.2);
    }
    a{
        color: blue;
    }
    .projects article{
        background-color: #daeaf6;
        padding: 0.5rem;
        margin: 1rem 0;
        border-radius: 5px;
        box-shadow: 5px 5px rgba(0, 0, 0, 0.2);
    }
</style>