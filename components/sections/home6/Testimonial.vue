<template>
  <section class="testimonial-section-two pb-60">
    <div class="auto-container">
      <div class="row">
        <!-- Title Column -->
        <div class="title-column col-xl-3 col-lg-12">
          <div class="sec-title">
            <span class="sub-title">Our feedbacks</span>
            <h3>What They’re Talking About Company</h3>
            <div class="text">Lorem Ipsum. Proin gravida nibh vel velit auctor aliquet. Aenean solldin, lorem is
            simply free text quis bibendum.</div>
          </div>
        </div>

        <!-- Testimonial Column -->
        <div class="testimonial-column col-xl-9 col-lg-12">
          <div class="inner-column">
            <!-- Testimonial Carousel -->
            <swiper :slides-per-view="3" :space-between="10" :loop="true" :autoplay="{
              delay: 8000,
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
              },
              991: {
                slidesPerView: 3,
                // spaceBetween: 30,
              },
              1199: {
                slidesPerView: 3,
                // spaceBetween: 30,
              },
              1350: {
                slidesPerView: 3,
                // spaceBetween: 30,
              },
            }" :pagination="{
              el: '.swiper-pagination',
              clickable: true,
            }" :navigation="{
              nextEl: '.h1n',
              prevEl: '.h1p',
            }" :modules="modules" class="testimonial-carousel owl-carousel owl-theme">

            <!-- Testimonial Block -->
            <swiper-slide class="testimonial-block-two">
              <div class="inner-box">
                <div class="content-box">
                  <div class="rating"><i class="fa fa-star"></i><i class="fa fa-star"></i><i
                    class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
                  </div>
                  <div class="text">Lorem ipsum is simply free text dolor not sit amet, notted
                  adipisicing elit sed do eiusmod incididunt labore et dolore text.</div>
                </div>
                <div class="info-box">
                  <div class="thumb"><img src="/images/resource/testi-thumb-4.jpg" alt=""></div>
                  <h6 class="name">Sarah Albert</h6>
                  <span class="designation">Designer</span>
                </div>
              </div>
            </swiper-slide>

            <!-- Testimonial Block -->
            <swiper-slide class="testimonial-block-two">
              <div class="inner-box">
                <div class="content-box">
                  <div class="rating"><i class="fa fa-star"></i><i class="fa fa-star"></i><i
                    class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
                  </div>
                  <div class="text">Lorem ipsum is simply free text dolor not sit amet, notted
                  adipisicing elit sed do eiusmod incididunt labore et dolore text.</div>
                </div>
                <div class="info-box">
                  <div class="thumb"><img src="/images/resource/testi-thumb-5.jpg" alt=""></div>
                  <h6 class="name">Mike Hardson</h6>
                  <span class="designation">Designer</span>
                </div>
              </div>
            </swiper-slide>

            <!-- Testimonial Block -->
            <swiper-slide class="testimonial-block-two">
              <div class="inner-box">
                <div class="content-box">
                  <div class="rating"><i class="fa fa-star"></i><i class="fa fa-star"></i><i
                    class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
                  </div>
                  <div class="text">Lorem ipsum is simply free text dolor not sit amet, notted
                  adipisicing elit sed do eiusmod incididunt labore et dolore text.</div>
                </div>
                <div class="info-box">
                  <div class="thumb"><img src="/images/resource/testi-thumb-6.jpg" alt=""></div>
                  <h6 class="name">Jessica Brown</h6>
                  <span class="designation">Designer</span>
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