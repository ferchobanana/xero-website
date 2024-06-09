<script lang="ts">  
    import Header from "$lib/components/Header.svelte"
</script>

    <div class="hero">
        <h1>Crea sitios web con Inteligencia artificial</h1>
        <p>Que vendan</p>

        <a class="cta" href="/">Crear cuenta gratis</a>
    </div>

<style>
    .hero {
        width: 100%;
        margin-top: 100px;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding: 15px;
    }
    h1 {
        text-align: center;
        font-size: 60px;
        font-weight: 900;
        text-transform: uppercase;
        width: 800px;
    }
    p {
        font-size: 35px;
    }
    .cta {
        margin-top: 30px;
        padding: 20px 60px;
        border-radius: 4px;
        background-color: #000;
        font-weight: 500;
        text-decoration: none;
        color: #fff;
    }
</style>