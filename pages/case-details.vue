< >
    <div class="main-container">
        <Header />
        <OffCanvasMobileMenu />
        <Breadcrumb title="Digital Marketing" active-title="Case Details" />
        <CaseDetailsCarousel />
        <CaseDetailsContent />
        <CaseDetailsNavigation />
        <CommentFormWrapper />
        <Footer />
    </div>
</ >

<script>
    export default {
        components: {
            Header: () => import('@/components/Header'),
            OffCanvasMobileMenu: () => import('@/components/OffCanvasMobileMenu'),
            Breadcrumb: () => import('@/components/Breadcrumb'),
            CaseDetailsCarousel: () => import('@/components/CaseDetailsCarousel'),
            CaseDetailsContent: () => import('@/components/CaseDetailsContent'),
            CaseDetailsNavigation: () => import('@/components/CaseDetailsNavigation'),
            CommentFormWrapper: () => import('@/components/CommentFormWrapper'),
            Footer: () => import('@/components/Footer')
        }
    }
</script>


