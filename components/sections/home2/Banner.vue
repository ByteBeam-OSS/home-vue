
<template>
    <section class="banner-section">
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
				<div class="bg-image" style="background-image: url(images/main-slider/2.jpg);"></div>
				<div class="auto-container">
					<div class="content-box">
						<span class="sub-title animate-1">Solutions for your businesses</span>
						<h1 class="title animate-2">Innovative Tech <br>Solutions</h1>
						<div class="btn-box animate-3">
							<NuxtLink to="/page-about" class="theme-btn btn-style-one"><span class="btn-title">Explore More</span></NuxtLink>
							<NuxtLink @click="openVideo" class="play-btn lightbox-image"><i class="icon fa fa-play"></i> watch video</NuxtLink>
						</div>
					</div>
				</div>
			</swiper-slide>

			<!-- Slide Item -->
			<swiper-slide class="slide-item">
				<div class="bg-image" style="background-image: url(images/main-slider/1.jpg);"></div>
				<div class="auto-container">
					<div class="content-box">
						<span class="sub-title animate-1">Solutions for your businesses</span>
						<h1 class="title animate-2">Innovative Tech <br>Solutions</h1>
						<div class="btn-box animate-3">
							<NuxtLink to="/page-about" class="theme-btn btn-style-one"><span class="btn-title">Explore More</span></NuxtLink>
							<NuxtLink @click="openVideo" class="play-btn lightbox-image"><i class="icon fa fa-play"></i> watch video</NuxtLink>
						</div>
					</div>
				</div>
			</swiper-slide>
		</swiper>
	</section>
    <modal-video :channel="videoChannel" :videoId="videoId" v-model:isOpen="videoIsOpen" />
</template>
<script>
import { Autoplay, Navigation, Pagination } from "swiper/modules"
import { Swiper, SwiperSlide } from "swiper/vue"
import ModalVideo from '../../components/elements/ModalVideo.vue'

export default {
    components: {
        Swiper,
        SwiperSlide,
        ModalVideo
    },
    setup() {
        return {
            modules: [Autoplay, Pagination, Navigation],
        }
    },

    data: () => {
        return {
            videoIsOpen: false
        }
    },
    methods: {
        openVideo() {
            this.videoIsOpen = !this.videoIsOpen
        }
    },
    computed: {
        videoChannel: function () {
            //Logic to extract based on URL
            return 'youtube'
        },
        videoId: function () {
            //Logic to extract based on URL
            return 'QiqQoqtnHrk'
        }
    }
}
</script>