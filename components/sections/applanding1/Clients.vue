<template>
  <section class="clients-section client_top">
    <div class="auto-container">
      <!-- Sponsors Outer -->
      <div class="sponsors-outer">
        <h4>Our company have worked with</h4>
        <!--clients carousel-->
        <swiper :slides-per-view="5" :space-between="30" :loop="true" :autoplay="{
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
            slidesPerView: 3,
            spaceBetween: 30,
          },
          991: {
            slidesPerView: 4,
            spaceBetween: 30,
          },
          1199: {
            slidesPerView: 5,
            spaceBetween: 30,
          },
          1350: {
            slidesPerView: 5,
            spaceBetween: 30,
          },
        }" :pagination="{
          el: '.swiper-pagination',
          clickable: true,
        }" :navigation="{
          nextEl: '.h1n',
          prevEl: '.h1p',
        }" :modules="modules" 
        class="clients-carousel bg-remove owl-carousel owl-theme">
        <swiper-slide class="slide-item"> <NuxtLink to="#"><img src="/images/app/5.png" alt=""></NuxtLink></swiper-slide>
        <swiper-slide class="slide-item"> <NuxtLink to="#"><img src="/images/app/3.png" alt=""></NuxtLink></swiper-slide>
        <swiper-slide class="slide-item"> <NuxtLink to="#"><img src="/images/app/1-1.png" alt=""></NuxtLink></swiper-slide>
        <swiper-slide class="slide-item"> <NuxtLink to="#"><img src="/images/app/2-1.png" alt=""></NuxtLink></swiper-slide>
        <swiper-slide class="slide-item"> <NuxtLink to="#"><img src="/images/app/2-1.png" alt=""></NuxtLink></swiper-slide>
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