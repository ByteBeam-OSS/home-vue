<template>
  <section class="testimonial-section-five">
    <div class="auto-container">
      <!-- Title Column -->
      <div class="title-column col-xl-12 col-lg-12 col-md-12">
        <div class="inner-column">
          <div class="sec-title text-center">
            <span class="sub-title">CLIENT’S TESTIMONIALS</span>
            <h2>What They’re Talking About Us</h2>
          </div>
        </div>
      </div>
      <div class="row">
        <!-- Testimonial Column -->
        <div class="testimonial-column col-xl-12">
          <div class="inner-column">
            <!-- Testimonial Carousel -->
            <swiper :slides-per-view="2" :space-between="10" :loop="true" :autoplay="{
              delay: 12000,
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
            }" :modules="modules" class="testimonial-carousel-five owl-carousel owl-theme">

            <!-- Testimonial Block -->
            <swiper-slide class="testimonial-block-five">
              <div class="inner-box">
                <div class="content-box">
                  <span class="icon icon-quote"></span>
                  <div class="rating"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i></div>
                  <div class="text">Proin a lacus arcu. Nullam id dui eu orci maximus. Cras at auctor lectus, vel pretium tellus. Class aptent sociosqu ad litora torquent per conubia nostra.</div>
                </div>
                <div class="info-box">
                  <figure class="thumb"><img src="/images/resource/testi-thumb-3.jpg" alt=""></figure>
                  <h5 class="name">Jessica Brown</h5>
                  <span class="designation">Co Founder</span>
                </div>
              </div>
            </swiper-slide>

            <!-- Testimonial Block -->
            <swiper-slide class="testimonial-block-five">
              <div class="inner-box">
                <div class="content-box">
                  <span class="icon icon-quote"></span>
                  <div class="rating"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i></div>
                  <div class="text">Proin a lacus arcu. Nullam id dui eu orci maximus. Cras at auctor lectus, vel pretium tellus. Class aptent sociosqu ad litora torquent per conubia nostra.</div>
                </div>
                <div class="info-box">
                  <figure class="thumb"><img src="/images/resource/testi-thumb-2.jpg" alt=""></figure>
                  <h5 class="name">Jessica Brown</h5>
                  <span class="designation">Co Founder</span>
                </div>
              </div>
            </swiper-slide>

            <!-- Testimonial Block -->
            <swiper-slide class="testimonial-block-five">
              <div class="inner-box">
                <div class="content-box">
                  <span class="icon icon-quote"></span>
                  <div class="rating"><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i></div>
                  <div class="text">Proin a lacus arcu. Nullam id dui eu orci maximus. Cras at auctor lectus, vel pretium tellus. Class aptent sociosqu ad litora torquent per conubia nostra.</div>
                </div>
                <div class="info-box">
                  <figure class="thumb"><img src="/images/resource/testi-thumb-1.jpg" alt=""></figure>
                  <h5 class="name">Jessica Brown</h5>
                  <span class="designation">Co Founder</span>
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