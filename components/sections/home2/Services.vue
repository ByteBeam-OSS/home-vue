

<template>
    <section class="services-section-two">
        <div class="auto-container">
            <div class="row">
                <div class="title-column col-lg-5 col-md-12">
                    <div class="sec-title light">
                        <span class="sub-title">What we offer</span>
                        <h2>Help you Overcome your Technology Challenges</h2>
                        <NuxtLink to="/page-services" class="theme-btn btn-style-one"><span class="btn-title">Discover
                                more</span></NuxtLink>
                    </div>
                </div>

                <div class="services-column col-lg-7 col-md-12">
                    <div class="inner-column">
                        <!-- Services Carousel Two -->
                        <div class="swiper-container services-carousel-two">
                            <swiper :slides-per-view="5" :space-between="10" :loop="true" :autoplay="{
                                delay: 8000,
                                disableOnInteraction: true,
                            }" :breakpoints="{
    320: {
        slidesPerView: 1,
        spaceBetween: 10,
    },
    575: {
        slidesPerView: 2,
        spaceBetween: 10,
    },
    767: {
        slidesPerView: 3,
        spaceBetween: 10,
    },
    991: {
        slidesPerView: 4,
        spaceBetween: 10,
    },
    1199: {
        slidesPerView: 4,
        spaceBetween: 10,
    },
    1350: {
        slidesPerView: 5,
        spaceBetween: 10,
    },
}" :pagination="{
    el: '.swiper-pagination',
    clickable: true,
}" :navigation="{
    nextEl: '.h1n',
    prevEl: '.h1p',
}" :modules="modules" class="swiper-wrapper">
                                <!-- Service Block Two -->
                                <swiper-slide class="swiper-slide service-block-two">
                                    <div class="inner-box">
                                        <div class="icon fa fa-globe"></div>
                                        <h6 class="title"><NuxtLink to="/page-service-details">Website</NuxtLink></h6>
                                    </div>
                                </swiper-slide>

                                <!-- Service Block Two -->
                                <swiper-slide class="swiper-slide service-block-two">
                                    <div class="inner-box">
                                        <div class="icon fab fa-apple"></div>
                                        <h6 class="title"><NuxtLink to="/page-service-details">IOS</NuxtLink></h6>
                                    </div>
                                </swiper-slide>

                                <!-- Service Block Two -->
                                <swiper-slide class="swiper-slide service-block-two">
                                    <div class="inner-box">
                                        <div class="icon fab fa-android"></div>
                                        <h6 class="title"><NuxtLink to="/page-service-details">Android</NuxtLink></h6>
                                    </div>
                                </swiper-slide>

                                <!-- Service Block Two -->
                                <swiper-slide class="swiper-slide service-block-two">
                                    <div class="inner-box">
                                        <div class="icon fab fa-ioxhost"></div>
                                        <h6 class="title"><NuxtLink to="/page-service-details">IOT</NuxtLink></h6>
                                    </div>
                                </swiper-slide>

                                <!-- Service Block Two -->
                                <swiper-slide class="swiper-slide service-block-two">
                                    <div class="inner-box">
                                        <div class="icon fa fa-tv"></div>
                                        <h6 class="title"><NuxtLink to="/page-service-details">Television</NuxtLink></h6>
                                    </div>
                                </swiper-slide>

                            </swiper>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
import { Autoplay, Navigation, Pagination } from "swiper/modules"
import { Swiper, SwiperSlide } from "swiper/vue"

export default {
    components: {
        Swiper,
        SwiperSlide,
    },
    setup() {
        return {
            modules: [Autoplay, Pagination, Navigation],
        }
    },
}
</script>