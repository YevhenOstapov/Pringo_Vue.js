< >
    <div class="service-carousel-section">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="service-carousel position-relative">
                        <swiper
                            :speed="1000"
                            :navigation="serviceCarousel.navigation"
                            :loop="true"
                        >
                            <swiper-slide class="service-carousel-content">
                                <img class="service-img" src="/images/service/1.jpg" alt="images-not_found" />
                            </swiper-slide>
                        </swiper>
                        <!-- If we need navigation buttons -->
                        <div class="d-none d-md-block">
                            <div class="service-carousel swiper-button-prev">
                                <i class="icofont-double-left"></i>
                            </div>
                            <div class="service-carousel swiper-button-next">
                                <i class="icofont-double-right"></i>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</ >

<script>
    import { Swiper, SwiperSlide } from "swiper/vue"
    import SwiperCore, { Navigation } from 'swiper/core'
    SwiperCore.use([Navigation])

    export default {
        components: {
            Swiper,
            SwiperSlide
        },
        data() {
            return {
                serviceCarousel: {
                    navigation: {
                        nextEl: ".service-carousel .swiper-button-next",
                        prevEl: ".service-carousel .swiper-button-prev",
                    },
                }
            }
        },
    };
</script>