<template>
  <section class="team-section-ten">
    <div class="auto-container">
      <div class="row">
        <!-- Title Column -->
        <div class="title-column col-xl-4 col-lg-4 col-md-12">
          <div class="inner-column">
            <div class="sec-title">
              <span class="sub-title">our Expart Members</span>
              <h2>Professional Expert Team</h2>
              <div class="text">There are many variations of passages of ipsum available, but the majority have suffered alteration in form.</div>
            </div>
          </div>
        </div>

        <!-- Carousel Column -->
        <div class="carousel-column col-xl-8 col-lg-8 col-md-12">
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
                  slidesPerView: 2,
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
              class="news-carousel owl-carousel owl-theme">
              <!-- News Block -->
                <swiper-slide class="team-block-ten">
                  <div class="inner-box">
                    <div class="image-box">
                      <figure class="image"><NuxtLink to="page-team-details"><img src="/images/resource/team-4.jpg" alt=""></NuxtLink></figure>
                    </div>
                    <div class="info-box">
                      <h5 class="name"><NuxtLink to="page-team-details">Adman Michel</NuxtLink></h5>
                      <span class="share-icon fa fa-share-alt"></span>
                      <div class="social-links">
                        <NuxtLink to="#"><i class="fab fa-twitter"></i></NuxtLink>
                        <NuxtLink to="#"><i class="fab fa-facebook-f"></i></NuxtLink>
                        <NuxtLink to="#"><i class="fab fa-pinterest-p"></i></NuxtLink>
                        <NuxtLink to="#"><i class="fab fa-instagram"></i></NuxtLink>
                      </div>
                    </div>
                  </div>
                </swiper-slide>

                <!-- News Block -->
                <swiper-slide class="team-block-ten">
                  <div class="inner-box">
                    <div class="image-box">
                      <figure class="image"><NuxtLink to="page-team-details"><img src="/images/resource/team-4.jpg" alt=""></NuxtLink></figure>
                    </div>
                    <div class="info-box">
                      <h5 class="name"><NuxtLink to="page-team-details">Adman Michel</NuxtLink></h5>
                      <span class="share-icon fa fa-share-alt"></span>
                      <div class="social-links">
                        <NuxtLink to="#"><i class="fab fa-twitter"></i></NuxtLink>
                        <NuxtLink to="#"><i class="fab fa-facebook-f"></i></NuxtLink>
                        <NuxtLink to="#"><i class="fab fa-pinterest-p"></i></NuxtLink>
                        <NuxtLink to="#"><i class="fab fa-instagram"></i></NuxtLink>
                      </div>
                    </div>
                  </div>
                </swiper-slide>

                <!-- News Block -->
                <swiper-slide class="team-block-ten">
                  <div class="inner-box">
                    <div class="image-box">
                      <figure class="image"><NuxtLink to="page-team-details"><img src="/images/resource/team-4.jpg" alt=""></NuxtLink></figure>
                    </div>
                    <div class="info-box">
                      <h5 class="name"><NuxtLink to="page-team-details">Adman Michel</NuxtLink></h5>
                      <span class="share-icon fa fa-share-alt"></span>
                      <div class="social-links">
                        <NuxtLink to="#"><i class="fab fa-twitter"></i></NuxtLink>
                        <NuxtLink to="#"><i class="fab fa-facebook-f"></i></NuxtLink>
                        <NuxtLink to="#"><i class="fab fa-pinterest-p"></i></NuxtLink>
                        <NuxtLink to="#"><i class="fab fa-instagram"></i></NuxtLink>
                      </div>
                    </div>
                  </div>
                </swiper-slide>

                <!-- News Block -->
                <swiper-slide class="team-block-ten">
                  <div class="inner-box">
                    <div class="image-box">
                      <figure class="image"><NuxtLink to="page-team-details"><img src="/images/resource/team-4.jpg" alt=""></NuxtLink></figure>
                    </div>
                    <div class="info-box">
                      <h5 class="name"><NuxtLink to="page-team-details">Adman Michel</NuxtLink></h5>
                      <span class="share-icon fa fa-share-alt"></span>
                      <div class="social-links">
                        <NuxtLink to="#"><i class="fab fa-twitter"></i></NuxtLink>
                        <NuxtLink to="#"><i class="fab fa-facebook-f"></i></NuxtLink>
                        <NuxtLink to="#"><i class="fab fa-pinterest-p"></i></NuxtLink>
                        <NuxtLink to="#"><i class="fab fa-instagram"></i></NuxtLink>
                      </div>
                    </div>
                  </div>
                </swiper-slide>

                <!-- News Block -->
                <swiper-slide class="team-block-ten">
                  <div class="inner-box">
                    <div class="image-box">
                      <figure class="image"><NuxtLink to="page-team-details"><img src="/images/resource/team-4.jpg" alt=""></NuxtLink></figure>
                    </div>
                    <div class="info-box">
                      <h5 class="name"><NuxtLink to="page-team-details">Adman Michel</NuxtLink></h5>
                      <span class="share-icon fa fa-share-alt"></span>
                      <div class="social-links">
                        <NuxtLink to="#"><i class="fab fa-twitter"></i></NuxtLink>
                        <NuxtLink to="#"><i class="fab fa-facebook-f"></i></NuxtLink>
                        <NuxtLink to="#"><i class="fab fa-pinterest-p"></i></NuxtLink>
                        <NuxtLink to="#"><i class="fab fa-instagram"></i></NuxtLink>
                      </div>
                    </div>
                  </div>
                </swiper-slide>

                <!-- News Block -->
                <swiper-slide class="team-block-ten">
                  <div class="inner-box">
                    <div class="image-box">
                      <figure class="image"><NuxtLink to="page-team-details"><img src="/images/resource/team-4.jpg" alt=""></NuxtLink></figure>
                    </div>
                    <div class="info-box">
                      <h5 class="name"><NuxtLink to="page-team-details">Adman Michel</NuxtLink></h5>
                      <span class="share-icon fa fa-share-alt"></span>
                      <div class="social-links">
                        <NuxtLink to="#"><i class="fab fa-twitter"></i></NuxtLink>
                        <NuxtLink to="#"><i class="fab fa-facebook-f"></i></NuxtLink>
                        <NuxtLink to="#"><i class="fab fa-pinterest-p"></i></NuxtLink>
                        <NuxtLink to="#"><i class="fab fa-instagram"></i></NuxtLink>
                      </div>
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