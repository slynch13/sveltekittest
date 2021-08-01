<script>
    import Header from '$lib/header.svelte'
    import "../styles/tailwind-output.css"
</script>
<div >
    <Header></Header>
    <main>
        <slot></slot>
    </main>
</div>


