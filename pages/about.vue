< >
    <div class="main-container">
        <Header />
        <OffCanvasMobileMenu />
        <Breadcrumb title="About Us" active-title="About Us" />
        <AboutTwo />
        <AboutOne />
        <TeamSection />
        <TestimonialOne />
        <Footer />
    </div>
</ >

<script>
    export default {
        components: {
            Header: () => import('@/components/Header'),
            OffCanvasMobileMenu: () => import('@/components/OffCanvasMobileMenu'),
            Breadcrumb: () => import('@/components/Breadcrumb'),
            AboutTwo: () => import('@/components/AboutTwo'),
            AboutOne: () => import('@/components/AboutOne'),
            TeamSection: () => import('@/components/TeamSection'),
            TestimonialOne: () => import('@/components/TestimonialOne'),
            Footer: () => import('@/components/Footer')
        },
    };
</script>


