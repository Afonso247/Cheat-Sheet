<script>
    import Titulo from '$lib/titulo.svelte';
    import '../styles/global.css';
</script>


<header>
    <nav>
        <Titulo />
        <div class="links">
            <a href="/">Início</a>
            <a href="/projetos">Meus projetos</a>
            <a href="/sobre">Sobre mim</a>
        </div>
    </nav>
</header>
<main>
    <!-- Conteúdo da página -->
    <slot></slot>
</main>
<footer>
    <h4>Criado por Afonso H.</h4>
    <p>Github:<a href="https://github.com/Afonso247" 
                style="text-decoration: none;font-weight: bold;" target="_blank"
                >Afonso247</a></p>
</footer>


<style>
    header {
        text-align: center;
        background: rgba(0, 0, 0, 0.1);
    }
    main {
        max-width: 960px;
        margin: 2rem auto;
    }
    footer {
        margin-top: 5rem;
        text-align: center;
    }
    .links {
        margin-left: auto;
    }
    a {
        margin-left: 1rem;
    }
    nav {
        display: flex;
        align-items: center;
        max-width: 960px;
        margin: 0 auto;
    }
</style>