<template>
  <section class="news-section-9layout">
    <div class="auto-container">
      <div class="row">
        <!-- Title Column -->
        <div class="title-column col-lg-4">
          <div class="inner-column">
            <div class="sec-title">
              <span class="sub-title">from the blog</span>
              <h2>Our L atest News & Articles from the Blog</h2>
              <div class="text">There are many variations of passages of ipsum available, but the majority have suffered alteration in form.</div>
            </div>
          </div>
        </div>

        <!-- Carousel Column -->
        <div class="carousel-column col-lg-8">
          <div class="carousel-outer">
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
              <swiper-slide class="news-block-layout-9">
                <div class="inner-box">
                  <div class="image-box">
                    <figure class="image"><NuxtLink to="news-details"><img src="/images/resource/news-1.jpg" alt=""></NuxtLink></figure>
                    <span class="date"><b>28</b> OCT</span>
                  </div>
                  <div class="content-box">
                    <ul class="post-info">
                      <li><i class="fa fa-user"></i> by Admin</li>
                      <li><i class="fa fa-tag"></i> Technology</li>
                    </ul>
                    <h4 class="title"><NuxtLink to="news-details">Professional technology information & solutions are just like…</NuxtLink></h4>
                  </div>
                  <div class="bottom-box">
                    <NuxtLink to="news-details" class="read-more">Read More <i class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                    <div class="comments"><i class="fa fa-comments"></i> 02</div>
                  </div>
                </div>
              </swiper-slide>

              <!-- News Block -->
              <swiper-slide class="news-block-layout-9">
                <div class="inner-box">
                  <div class="image-box">
                    <figure class="image"><NuxtLink to="news-details"><img src="/images/resource/news-2.jpg" alt=""></NuxtLink></figure>
                    <span class="date"><b>28</b> OCT</span>
                  </div>
                  <div class="content-box">
                    <ul class="post-info">
                      <li><i class="fa fa-user"></i> by Admin</li>
                      <li><i class="fa fa-tag"></i> Technology</li>
                    </ul>
                    <h4 class="title"><NuxtLink to="news-details">Professional technology information & solutions are just like…</NuxtLink></h4>
                  </div>
                  <div class="bottom-box">
                    <NuxtLink to="news-details" class="read-more">Read More <i class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                    <div class="comments"><i class="fa fa-comments"></i> 02</div>
                  </div>
                </div>
              </swiper-slide>

              <!-- News Block -->
              <swiper-slide class="news-block-layout-9">
                <div class="inner-box">
                  <div class="image-box">
                    <figure class="image"><NuxtLink to="news-details"><img src="/images/resource/news-3.jpg" alt=""></NuxtLink></figure>
                    <span class="date"><b>28</b> OCT</span>
                  </div>
                  <div class="content-box">
                    <ul class="post-info">
                      <li><i class="fa fa-user"></i> by Admin</li>
                      <li><i class="fa fa-tag"></i> Technology</li>
                    </ul>
                    <h4 class="title"><NuxtLink to="news-details">Professional technology information & solutions are just like…</NuxtLink></h4>
                  </div>
                  <div class="bottom-box">
                    <NuxtLink to="news-details" class="read-more">Read More <i class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                    <div class="comments"><i class="fa fa-comments"></i> 02</div>
                  </div>
                </div>
              </swiper-slide>

              <!-- News Block -->
              <swiper-slide class="news-block-layout-9">
                <div class="inner-box">
                  <div class="image-box">
                    <figure class="image"><NuxtLink to="news-details"><img src="/images/resource/news-1.jpg" alt=""></NuxtLink></figure>
                    <span class="date"><b>28</b> OCT</span>
                  </div>
                  <div class="content-box">
                    <ul class="post-info">
                      <li><i class="fa fa-user"></i> by Admin</li>
                      <li><i class="fa fa-tag"></i> Technology</li>
                    </ul>
                    <h4 class="title"><NuxtLink to="news-details">Professional technology information & solutions are just like…</NuxtLink></h4>
                  </div>
                  <div class="bottom-box">
                    <NuxtLink to="news-details" class="read-more">Read More <i class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                    <div class="comments"><i class="fa fa-comments"></i> 02</div>
                  </div>
                </div>
              </swiper-slide>

              <!-- News Block -->
              <swiper-slide class="news-block-layout-9">
                <div class="inner-box">
                  <div class="image-box">
                    <figure class="image"><NuxtLink to="news-details"><img src="/images/resource/news-2.jpg" alt=""></NuxtLink></figure>
                    <span class="date"><b>28</b> OCT</span>
                  </div>
                  <div class="content-box">
                    <ul class="post-info">
                      <li><i class="fa fa-user"></i> by Admin</li>
                      <li><i class="fa fa-tag"></i> Technology</li>
                    </ul>
                    <h4 class="title"><NuxtLink to="news-details">Professional technology information & solutions are just like…</NuxtLink></h4>
                  </div>
                  <div class="bottom-box">
                    <NuxtLink to="news-details" class="read-more">Read More <i class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                    <div class="comments"><i class="fa fa-comments"></i> 02</div>
                  </div>
                </div>
              </swiper-slide>

              <!-- News Block -->
              <swiper-slide class="news-block-layout-9">
                <div class="inner-box">
                  <div class="image-box">
                    <figure class="image"><NuxtLink to="news-details"><img src="/images/resource/news-3.jpg" alt=""></NuxtLink></figure>
                    <span class="date"><b>28</b> OCT</span>
                  </div>
                  <div class="content-box">
                    <ul class="post-info">
                      <li><i class="fa fa-user"></i> by Admin</li>
                      <li><i class="fa fa-tag"></i> Technology</li>
                    </ul>
                    <h4 class="title"><NuxtLink to="news-details">Professional technology information & solutions are just like…</NuxtLink></h4>
                  </div>
                  <div class="bottom-box">
                    <NuxtLink to="news-details" class="read-more">Read More <i class="fa fa-long-arrow-alt-right"></i></NuxtLink>
                    <div class="comments"><i class="fa fa-comments"></i> 02</div>
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