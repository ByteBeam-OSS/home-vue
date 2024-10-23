

<template>
    <section class="features-section-three">
        <div class="carousel-outer">
            <swiper
    :slides-per-view="3"
    :space-between="30"
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
     class="features-carousel owl-carousel owl-theme">
                <!-- Feature Block Three -->
                <swiper-slide class="feature-block-three">
                    <div class="inner-box ">
                        <figure class="image">
                            <NuxtLink to="/page-about"><img src="/images/resource/feature-1.jpg" alt=""></NuxtLink>
                            <span class="icon">G</span>
                        </figure>
                        <h4 class="title"><NuxtLink to="/page-about">Gaming and Enterteiment</NuxtLink></h4>
                        <h4 class="title"><NuxkLink href="page-about"></NuxkLink></h4>
                        <div class="text">There are many variations of passages of ipsum available, but the majority have suffered alteration in form.</div>
                    </div>
                </swiper-slide>

                <!-- Feature Block Three -->
                <swiper-slide class="feature-block-three">
                    <div class="inner-box ">
                        <figure class="image">
                            <NuxtLink to="/page-about"><img src="/images/resource/feature-2.jpg" alt=""></NuxtLink>
                            <span class="icon">G</span>
                        </figure>
                        <h4 class="title"><NuxtLink to="/page-about">Business and Finance</NuxtLink></h4>
                        <div class="text">There are many variations of passages of ipsum available, but the majority have suffered alteration in form.</div>
                    </div>
                </swiper-slide>

                <!-- Feature Block Three -->
                <swiper-slide class="feature-block-three">
                    <div class="inner-box ">
                        <figure class="image">
                            <NuxtLink to="/page-about"><img src="/images/resource/feature-3.jpg" alt=""></NuxtLink>
                            <span class="icon">G</span>
                        </figure>
                        <h4 class="title"><NuxtLink to="/page-about">Business and Finance</NuxtLink></h4>
                        <div class="text">There are many variations of passages of ipsum available, but the majority have suffered alteration in form.</div>
                    </div>
                </swiper-slide>
            </swiper>
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