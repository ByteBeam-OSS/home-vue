

<template>
    <section class="testimonial-section-four">
        <div class="auto-container">
            <div class="row">
                <!-- Title Column -->
                <div class="title-column col-xl-5 col-lg-6 col-md-12">
                    <div class="inner-column">
                        <div class="sec-title">
                            <span class="sub-title">Our feedbacks</span>
                            <h2>What They’re Talking About Us</h2>
                            <div class="text">There are many variations of passages the majority have suffered alteration in
                                some fo injected humour, or randomised words believable.</div>
                        </div>
                    </div>
                </div>

                <!-- Testimonial Column -->
                <div class="testimonial-column col-xl-7 col-lg-6 col-md-12">
                    <div class="carousel-outer">
                        <div class="testimonial-bg" style="background-image: url(images/resource/testimonial-bg.png)"></div>
                        <swiper
    :slides-per-view="1"
    :space-between="30"
    :loop="true"
    :autoplay="{
      delay: 8000,
      disableOnInteraction: true,
    }"
    :pagination="{
      el: '.swiper-pagination',
      clickable: true,
    }"
    :navigation="{
      nextEl: '.h1n',
      prevEl: '.h1p',
    }"
    :modules="modules" class="testimonial-carousel-four owl-carousel owl-theme">

                            <!-- Testimonial Block Four -->
                            <swiper-slide class="testimonial-block-four">
                                <div class="inner-box">
                                    <div class="content-box">
                                        <span class="icon icon-quote"></span>
                                        <div class="rating"><i class="fa fa-star"></i><i class="fa fa-star"></i><i
                                                class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
                                        </div>
                                        <div class="text">Proin a lacus arcu. Nullam id dui eu orci maximus. Cras at auctor
                                            lectus, vel pretium tellus. Class aptent sociosqu ad litora torquent per conubia
                                            nostra.</div>
                                    </div>
                                    <div class="info-box">
                                        <figure class="thumb"><img src="/images/resource/testi-thumb-3.jpg" alt=""></figure>
                                        <h5 class="name">Jessica Brown</h5>
                                        <span class="designation">Co Founder</span>
                                    </div>
                                </div>
                            </swiper-slide>

                            <!-- Testimonial Block Four -->
                            <swiper-slide class="testimonial-block-four">
                                <div class="inner-box">
                                    <div class="content-box">
                                        <span class="icon icon-quote"></span>
                                        <div class="rating"><i class="fa fa-star"></i><i class="fa fa-star"></i><i
                                                class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
                                        </div>
                                        <div class="text">Proin a lacus arcu. Nullam id dui eu orci maximus. Cras at auctor
                                            lectus, vel pretium tellus. Class aptent sociosqu ad litora torquent per conubia
                                            nostra.</div>
                                    </div>
                                    <div class="info-box">
                                        <figure class="thumb"><img src="/images/resource/testi-thumb-3.jpg" alt=""></figure>
                                        <h5 class="name">Jessica Brown</h5>
                                        <span class="designation">Co Founder</span>
                                    </div>
                                </div>
                            </swiper-slide>

                            <!-- Testimonial Block Four -->
                            <swiper-slide class="testimonial-block-four">
                                <div class="inner-box">
                                    <div class="content-box">
                                        <span class="icon icon-quote"></span>
                                        <div class="rating"><i class="fa fa-star"></i><i class="fa fa-star"></i><i
                                                class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
                                        </div>
                                        <div class="text">Proin a lacus arcu. Nullam id dui eu orci maximus. Cras at auctor
                                            lectus, vel pretium tellus. Class aptent sociosqu ad litora torquent per conubia
                                            nostra.</div>
                                    </div>
                                    <div class="info-box">
                                        <figure class="thumb"><img src="/images/resource/testi-thumb-3.jpg" alt=""></figure>
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