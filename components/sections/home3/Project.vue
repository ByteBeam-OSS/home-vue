

<template>
    <section class="project-section-three">
        <div class="auto-container">
            <div class="sec-title light">
                <div class="row align-items-center">
                    <div class="col-lg-7">
                        <span class="sub-title">recently Completed work</span>
                        <h2>Improve & Enhance the <br>Tech Projects</h2>
                    </div>
                    <div class="col-lg-5 text-end btn-box">
                        <NuxtLink to="page-projects" class="theme-btn btn-style-two bg-light"><span
                                class="btn-title text-black">View all work</span></NuxtLink>
                    </div>
                </div>
            </div>

            <div class="carousel-outer">
                <!-- Prject Carousel -->
                <swiper
    :slides-per-view="4"
    :space-between="20"
    :loop="true"
    :autoplay="{
      delay: 8000,
      disableOnInteraction: true,
    }"
    :breakpoints="{
      320: {
        slidesPerView: 1,
        // spaceBetween: 30,
      },
      575: {
        slidesPerView: 2,
        // spaceBetween: 30,
      },
      767: {
        slidesPerView: 2,
        // spaceBetween: 30,
      },
      991: {
        slidesPerView: 3,
        // spaceBetween: 30,
      },
      1199: {
        slidesPerView: 4,
        // spaceBetween: 30,
      },
      1350: {
        slidesPerView: 4,
        // spaceBetween: 30,
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
     class="project-carousel-three owl-carousel owl-theme">
                    <!-- Project Block Three-->
                    <swiper-slide class="project-block-three">
                        <div class="inner-box">
                            <div class="image-box">
                                <figure class="image"><NuxtLink to="images/resource/project-8.jpg" class="lightbox-image"><img
                                            src="/images/resource/project-8.jpg" alt=""></NuxtLink></figure>
                                <div class="overlay-box">
                                    <NuxtLink to="page-project-details" class="icon"><i
                                            class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                                    <h4 class="title"><NuxtLink to="/page-project-details">Tech Solutions</NuxtLink></h4>
                                    <span class="cat">DESIGN / IDEAS</span>
                                </div>
                            </div>
                        </div>
                    </swiper-slide>

                    <!-- Project Block Three-->
                    <swiper-slide class="project-block-three">
                        <div class="inner-box">
                            <div class="image-box">
                                <figure class="image"><NuxtLink to="images/resource/project-9.jpg" class="lightbox-image"><img
                                            src="/images/resource/project-9.jpg" alt=""></NuxtLink></figure>
                                <div class="overlay-box">
                                    <NuxtLink to="page-project-details" class="icon"><i
                                            class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                                    <h4 class="title"><NuxtLink to="/page-project-details">Tech Solutions</NuxtLink></h4>
                                    <span class="cat">DESIGN / IDEAS</span>
                                </div>
                            </div>
                        </div>
                    </swiper-slide>

                    <!-- Project Block Three-->
                    <swiper-slide class="project-block-three">
                        <div class="inner-box">
                            <div class="image-box">
                                <figure class="image"><NuxtLink to="images/resource/project-10.jpg" class="lightbox-image"><img
                                            src="/images/resource/project-10.jpg" alt=""></NuxtLink></figure>
                                <div class="overlay-box">
                                    <NuxtLink to="page-project-details" class="icon"><i
                                            class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                                    <h4 class="title"><NuxtLink to="/page-project-details">Tech Solutions</NuxtLink></h4>
                                    <span class="cat">DESIGN / IDEAS</span>
                                </div>
                            </div>
                        </div>
                    </swiper-slide>

                    <!-- Project Block Three-->
                    <swiper-slide class="project-block-three">
                        <div class="inner-box">
                            <div class="image-box">
                                <figure class="image"><NuxtLink to="images/resource/project-11.jpg" class="lightbox-image"><img
                                            src="/images/resource/project-11.jpg" alt=""></NuxtLink></figure>
                                <div class="overlay-box">
                                    <NuxtLink to="page-project-details" class="icon"><i
                                            class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                                    <h4 class="title"><NuxtLink to="/page-project-details">Tech Solutions</NuxtLink></h4>
                                    <span class="cat">DESIGN / IDEAS</span>
                                </div>
                            </div>
                        </div>
                    </swiper-slide>

                </swiper>
            </div>
        </div>
    </section>
</template>
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