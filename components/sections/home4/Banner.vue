<template>
    <section class="banner-section-three">
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
    :modules="modules"
     class="banner-carousel owl-carousel owl-theme">
			<!-- Slide Item -->
			<swiper-slide class="slide-item">
				<div class="bg-image" style="background-image: url(images/main-slider/4.jpg);"></div>
				<div class="auto-container">
					<div class="content-box">
						<h1 class="title animate-1">Innovations</h1>
						<h2 class="sub-title animate-2">Technolgy Partners</h2>
						<div class="btn-box animate-3">
							<NuxtLink to="/page-about" class="theme-btn btn-style-one hvr-light"><span class="btn-title">Discover more</span></NuxtLink>
						</div>
					</div>
				</div>
			</swiper-slide>

			<!-- Slide Item -->
			<swiper-slide class="slide-item">
				<div class="bg-image" style="background-image: url(images/main-slider/2.jpg);"></div>
				<div class="auto-container">
					<div class="content-box">
						<h1 class="title animate-1">Innovations</h1>
						<h2 class="sub-title animate-2">Technolgy Partners</h2>
						<div class="btn-box animate-3">
							<NuxtLink to="/page-about" class="theme-btn btn-style-one hvr-light"><span class="btn-title">Discover more</span></NuxtLink>
						</div>
					</div>
				</div>
			</swiper-slide>
		</swiper>
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