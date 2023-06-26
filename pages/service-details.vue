< >
    <div class="main-container">
        <Header />
        <OffCanvasMobileMenu />
        <Breadcrumb title="Service Details" active-title="Service Details" />
        <ServiceCarousel />
        <ServiceDetailsContent />
        <Footer />
    </div>
</ >

<script>
    export default {
        components: {
            Header: () => import('@/components/Header'),
            OffCanvasMobileMenu: () => import('@/components/OffCanvasMobileMenu'),
            Breadcrumb: () => import('@/components/Breadcrumb'),
            ServiceCarousel: () => import('@/components/ServiceCarousel'),
            ServiceDetailsContent: () => import('@/components/ServiceDetailsContent'),
            Footer: () => import('@/components/Footer'),
        }
    }
</script>


