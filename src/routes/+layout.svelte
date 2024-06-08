<script>
    import '../global.css'
    import Header from '$lib/components/Header.svelte';
</script>

<div>

    <Header></Header>

    <main>
        <slot></slot>
    </main>
</div>