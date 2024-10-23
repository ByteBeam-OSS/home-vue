<template>
  <section class="testimonial-section-three">
    <div class="auto-container">
      <div class="sec-title text-center">
        <span class="sub-title">Our feedbacks</span>
        <h2>What They’re Talking<br> About Company</h2>
      </div>
      <div class="row">
        <!-- Testimonial Column -->
        <div class="testimonial-column col-xl-12">
          <div class="inner-column">
            <!-- Testimonial Carousel -->
            <swiper :slides-per-view="3" :space-between="10" :loop="true" :autoplay="{
              delay: 2000,
              disableOnInteraction: true,
            }" :breakpoints="{
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
              }
            }" :pagination="{
              el: '.swiper-pagination',
              clickable: true,
            }" :navigation="{
              nextEl: '.h1n',
              prevEl: '.h1p',
            }" :modules="modules" class="testimonial-carousel-three owl-carousel owl-theme">

            <!-- Testimonial Block -->
            <swiper-slide class="testimonial-block-three">
              <div class="inner-box">
                <div class="image-box">
                  <figure class="thumb"><img src="/images/resource/test-thumb-7.jpg" alt=""></figure>
                  <span class="icon fa fa-quote-right"></span>
                </div>
                <div class="content-box">
                  <div class="info-box">
                    <div class="rating"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i></div>
                    <h5 class="name">Mike Hardson</h5>
                    <span class="designation">Designer</span>
                  </div>
                  <div class="text">We believe in four pillars of influence that drive our growth. This is ingrained in everything we do We use technology to create a better and smarter environment.</div>
                </div>
              </div>
            </swiper-slide>

            <!-- Testimonial Block -->
            <swiper-slide class="testimonial-block-three">
              <div class="inner-box">
                <div class="image-box">
                  <figure class="thumb"><img src="/images/resource/test-thumb-8.jpg" alt=""></figure>
                  <span class="icon fa fa-quote-right"></span>
                </div>
                <div class="content-box">
                  <div class="info-box">
                    <div class="rating"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i></div>
                    <h5 class="name">Jessica Brown</h5>
                    <span class="designation">Designer</span>
                  </div>
                  <div class="text">We believe in four pillars of influence that drive our growth. This is ingrained in everything we do We use technology to create a better and smarter environment.</div>
                </div>
              </div>
            </swiper-slide>

            <!-- Testimonial Block -->
            <swiper-slide class="testimonial-block-three">
              <div class="inner-box">
                <div class="image-box">
                  <figure class="thumb"><img src="/images/resource/test-thumb-7.jpg" alt=""></figure>
                  <span class="icon fa fa-quote-right"></span>
                </div>
                <div class="content-box">
                  <div class="info-box">
                    <div class="rating"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i></div>
                    <h5 class="name">Jessica Brown</h5>
                    <span class="designation">Designer</span>
                  </div>
                  <div class="text">We believe in four pillars of influence that drive our growth. This is ingrained in everything we do We use technology to create a better and smarter environment.</div>
                </div>
              </div>
            </swiper-slide>
          </swiper>
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