<script>
    import '../global.css'
    import Header from '$lib/components/Header.svelte';
    import Footer from '$lib/components/Footer.svelte'
</script>

<div>

    <Header></Header>

    <main>
        <slot></slot>
    </main>

    <Footer></Footer>

</div>