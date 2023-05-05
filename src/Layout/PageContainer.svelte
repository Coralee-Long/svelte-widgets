<script>
    import Header from "/src/Layout/Header.svelte"
    import Footer from "/src/Layout/Footer.svelte"

    import "/src/Layout/PageContainer.css"
</script>

<div class="pageContainer">
    <Header />
    <div class="content-container">
        <slot><!-- optional fallback --></slot>
    </div>
    <Footer />
</div>
