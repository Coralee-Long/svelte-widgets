<script>
    import Header from "/src/components/Layout/Header.svelte"
    import Footer from "/src/components/Layout/Footer.svelte"

    import "/src/components/Layout/PageContainer.css"
</script>

<div class="pageContainer">
    <Header />
    <slot><!-- optional fallback --></slot>
    <Footer />
</div>
