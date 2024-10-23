
<template>
    <section class="banner-section-four">
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
    :modules="modules" class="banner-carousel owl-carousel owl-theme">
			<!-- Slide Item -->
			<swiper-slide class="slide-item">
				<div class="bg-image" style="background-image: url(images/main-slider/5.jpg);"></div>
				<div class="auto-container">
					<div class="content-box">
						<h1 class="title animate-1">Tools For <br>Development</h1>
						<div class="text animate-2">There are many of passages of lorem Ipsum, but the majori have<br> suffered alteration in some form.</div>
						<div class="btn-box animate-3">
							<NuxtLink to="/page-about" class="theme-btn btn-style-one hvr-light"><span class="btn-title">Discover more</span></NuxtLink>
						</div>
					</div>
				</div>
			</swiper-slide>

			<!-- Slide Item -->
			<swiper-slide class="slide-item">
				<div class="bg-image" style="background-image: url(images/main-slider/4.jpg);"></div>
				<div class="auto-container">
					<div class="content-box">
						<h1 class="title animate-1">Tools For <br>Development</h1>
						<div class="text animate-2">There are many of passages of lorem Ipsum, but the majori have<br> suffered
							alteration in some form.</div>
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