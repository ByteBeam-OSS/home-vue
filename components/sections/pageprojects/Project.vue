
<template>
    <section>
        <div class="container pb-0">

            <div class="carousel-outer">
                <!-- Prject Carousel -->
                <swiper :slides-per-view="4" :space-between="30" :loop="true" :autoplay="{
                    delay: 8000,
                    disableOnInteraction: true,
                }" :breakpoints="{
    320: {
        slidesPerView: 1,
        spaceBetween: 30,
    },
    575: {
        slidesPerView: 2,
        spaceBetween: 30,
    },
    767: {
        slidesPerView: 2,
        spaceBetween: 30,
    },
    991: {
        slidesPerView: 3,
        spaceBetween: 30,
    },
    1199: {
        slidesPerView: 4,
        spaceBetween: 30,
    },
    1350: {
        slidesPerView: 3,
        spaceBetween: 30,
    },
}" :pagination="{
    el: '.swiper-pagination',
    clickable: true,
}" :navigation="{
    nextEl: '.h1n',
    prevEl: '.h1p',
}" :modules="modules" class="project-carousel owl-carousel owl-theme">
                    <!-- Project Block -->
                    <swiper-slide class="project-block">
                        <div class="inner-box">
                            <div class="image-box">
                                <figure class="image"><NuxtLink to="images/resource/project-1.jpg" class="lightbox-image"><img
                                            src="/images/resource/project-1.jpg" alt=""></NuxtLink></figure>
                                <NuxtLink to="/page-project-details" class="icon"><i
                                        class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                            </div>
                            <div class="content-box">
                                <h4 class="title"><NuxtLink to="/page-project-details">Tech Solutions</NuxtLink></h4>
                                <span class="cat">DESIGN / IDEAS</span>
                            </div>
                        </div>
                    </swiper-slide>

                    <!-- Project Block -->
                    <swiper-slide class="project-block">
                        <div class="inner-box">
                            <div class="image-box">
                                <figure class="image"><NuxtLink to="images/resource/project-2.jpg" class="lightbox-image"><img
                                            src="/images/resource/project-2.jpg" alt=""></NuxtLink></figure>
                                <NuxtLink to="/page-project-details" class="icon"><i
                                        class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                            </div>
                            <div class="content-box">
                                <h4 class="title"><NuxtLink to="/page-project-details">Smart Visions</NuxtLink></h4>
                                <span class="cat">DESIGN / IDEAS</span>
                            </div>
                        </div>
                    </swiper-slide>

                    <!-- Project Block -->
                    <swiper-slide class="project-block">
                        <div class="inner-box">
                            <div class="image-box">
                                <figure class="image"><NuxtLink to="images/resource/project-3.jpg" class="lightbox-image"><img
                                            src="/images/resource/project-3.jpg" alt=""></NuxtLink></figure>
                                <NuxtLink to="/page-project-details" class="icon"><i
                                        class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                            </div>
                            <div class="content-box">
                                <h4 class="title"><NuxtLink to="/page-project-details">Platform Integration</NuxtLink></h4>
                                <span class="cat">DESIGN / IDEAS</span>
                            </div>
                        </div>
                    </swiper-slide>
                </swiper>
            </div>
        </div>
    </section>
    
    <section>
        <div class="container pt-3">

            <div class="carousel-outer">
                <!-- Prject Carousel -->
                <swiper :slides-per-view="4" :space-between="30" :loop="true" :autoplay="{
                    delay: 8000,
                    disableOnInteraction: true,
                }" :breakpoints="{
    320: {
        slidesPerView: 1,
        spaceBetween: 30,
    },
    575: {
        slidesPerView: 2,
        spaceBetween: 30,
    },
    767: {
        slidesPerView: 2,
        spaceBetween: 30,
    },
    991: {
        slidesPerView: 3,
        spaceBetween: 30,
    },
    1199: {
        slidesPerView: 4,
        spaceBetween: 30,
    },
    1350: {
        slidesPerView: 3,
        spaceBetween: 30,
    },
}" :pagination="{
    el: '.swiper-pagination',
    clickable: true,
}" :navigation="{
    nextEl: '.h1n',
    prevEl: '.h1p',
}" :modules="modules" class="project-carousel owl-carousel owl-theme">
                    <!-- Project Block -->
                    <swiper-slide class="project-block">
                        <div class="inner-box">
                            <div class="image-box">
                                <figure class="image"><NuxtLink to="images/resource/project-1.jpg" class="lightbox-image"><img
                                            src="/images/resource/project-1.jpg" alt=""></NuxtLink></figure>
                                <NuxtLink to="/page-project-details" class="icon"><i
                                        class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                            </div>
                            <div class="content-box">
                                <h4 class="title"><NuxtLink to="/page-project-details">Tech Solutions</NuxtLink></h4>
                                <span class="cat">DESIGN / IDEAS</span>
                            </div>
                        </div>
                    </swiper-slide>

                    <!-- Project Block -->
                    <swiper-slide class="project-block">
                        <div class="inner-box">
                            <div class="image-box">
                                <figure class="image"><NuxtLink to="images/resource/project-2.jpg" class="lightbox-image"><img
                                            src="/images/resource/project-2.jpg" alt=""></NuxtLink></figure>
                                <NuxtLink to="/page-project-details" class="icon"><i
                                        class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                            </div>
                            <div class="content-box">
                                <h4 class="title"><NuxtLink to="/page-project-details">Smart Visions</NuxtLink></h4>
                                <span class="cat">DESIGN / IDEAS</span>
                            </div>
                        </div>
                    </swiper-slide>

                    <!-- Project Block -->
                    <swiper-slide class="project-block">
                        <div class="inner-box">
                            <div class="image-box">
                                <figure class="image"><NuxtLink to="images/resource/project-3.jpg" class="lightbox-image"><img
                                            src="/images/resource/project-3.jpg" alt=""></NuxtLink></figure>
                                <NuxtLink to="/page-project-details" class="icon"><i
                                        class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                            </div>
                            <div class="content-box">
                                <h4 class="title"><NuxtLink to="/page-project-details">Platform Integration</NuxtLink></h4>
                                <span class="cat">DESIGN / IDEAS</span>
                            </div>
                        </div>
                    </swiper-slide>
                </swiper>
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