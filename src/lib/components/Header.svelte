<script>
    import Logo from "$lib/imgs/logo.png"
</script>

<header>

    <div class="logo">
        <img src={ Logo } alt="Logotipo Xeroweb">
    </div>

    <nav>
        <a href="/precios">Precios</a>
        <a href="/contacto">Contacto</a>
        <a href="/politicas-de-privacidad">Politicas</a>
        <a href="/condiciones-de-uso">Condiciones</a>
    </nav>

</header>

<style>
    header {
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 400px;
        padding: 20px 40px;
    }

    /* Logo */
    .logo {
        width: 250px;
    }
    .logo img {
        width: 100%;
    }

    /* Menu */
    nav {
        display: flex;
        gap: 20px;
    }

    nav a {
        font-size: 20px;
        font-weight: 500;
        color: #000;
        text-decoration: none;
    }
</style>