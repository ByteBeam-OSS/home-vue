

<template>
    <section class="project-section-two">
        <div class="auto-container">
            <div class="sec-title text-center">
                <span class="sub-title">recently Completed work</span>
                <h2>Improve & Enhance the <br>Tech Projects</h2>
            </div>

            <div class="carousel-outer">
                <!-- Prject Carousel -->
                <swiper
    :slides-per-view="3"
    :space-between="0"
    :loop="true"
    :autoplay="{
      delay: 8000,
      disableOnInteraction: true,
    }"
    :breakpoints="{
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
        slidesPerView: 2,
        spaceBetween: 30,
      },
      1199: {
        slidesPerView: 3,
        spaceBetween: 30,
      },
      1350: {
        slidesPerView: 3,
        spaceBetween: 30,
      },
    }"
    :pagination="{
      el: '.swiper-pagination',
      clickable: true,
    }"
    :navigation="{
      nextEl: '.h1n',
      prevEl: '.h1p',
    }"
    :modules="modules"
     class="project-carousel-two owl-carousel owl-theme">
                    <!-- Project Block Two -->
                    <swiper-slide class="project-block-two">
                        <div class="inner-box">
                            <div class="image-box">
                                <figure class="image"><NuxtLink to="/images/resource/project-5.jpg" class="lightbox-image"><img
                                            src="/images/resource/project-5.jpg" alt=""></NuxtLink></figure>
                            </div>
                            <div class="content-box">
                                <h5 class="title"><NuxtLink to="/page-project-details">Tech Solutions</NuxtLink></h5>
                                <span class="cat">DESIGN / IDEAS</span>
                                <NuxtLink to="page-project-details" class="icon"><i
                                        class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                            </div>
                        </div>
                    </swiper-slide>

                    <!-- Project Block Two -->
                    <swiper-slide class="project-block-two">
                        <div class="inner-box">
                            <div class="image-box">
                                <figure class="image"><NuxtLink to="/images/resource/project-6.jpg" class="lightbox-image"><img
                                            src="/images/resource/project-6.jpg" alt=""></NuxtLink></figure>
                            </div>
                            <div class="content-box">
                                <h5 class="title"><NuxtLink to="page-project-details">Smart Visions</NuxtLink></h5>
                                <span class="cat">DESIGN / IDEAS</span>
                                <NuxtLink to="page-project-details" class="icon"><i
                                        class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                            </div>
                        </div>
                    </swiper-slide>

                    <!-- Project Block Two -->
                    <swiper-slide class="project-block-two">
                        <div class="inner-box">
                            <div class="image-box">
                                <figure class="image"><NuxtLink to="/images/resource/project-7.jpg" class="lightbox-image"><img
                                            src="/images/resource/project-7.jpg" alt=""></NuxtLink></figure>
                            </div>
                            <div class="content-box">
                                <h5 class="title"><NuxtLink to="page-project-details">Platform Integration</NuxtLink></h5>
                                <span class="cat">DESIGN / IDEAS</span>
                                <NuxtLink to="page-project-details" class="icon"><i
                                        class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                            </div>
                        </div>
                    </swiper-slide>
            </swiper>
        </div>
    </div>
</section></template>
<script>
import { Swiper, SwiperSlide } from "swiper/vue";
import { Autoplay, Navigation, Pagination } from "swiper/modules";

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Autoplay, Pagination, Navigation],
    };
  },
};
</script>