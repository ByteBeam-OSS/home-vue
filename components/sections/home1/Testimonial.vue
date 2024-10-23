
<template>
    <section id="testimonials" class="testimonial-section">
        <div class="auto-container">
            <div class="sec-title">
                <span class="sub-title">Our feedbakcs</span>
                <h2>What They’re Talking<br> About Company</h2>
            </div>
            <div class="testimonials">
                <!-- Swiper -->
                <div class="swiper-container testimonial-content">
                    <swiper :slides-per-view="1" :space-between="30" :loop="true" :autoplay="{
                        delay: 8000,
                        disableOnInteraction: true,
                    }" :pagination="{
    el: '.swiper-pagination',
    clickable: true,
}" :navigation="{
    nextEl: '.h1n',
    prevEl: '.h1p',
}" :modules="modules" class="swiper-wrapper">
                        <!-- Testimonial Block Two -->
                        <swiper-slide class="testimonial-block swiper-slide">
                            <div class="row">
                                <div class="content-column col-lg-6 col-md-12">
                                    <div class="icon-box">
                                        <span class="icon icon-quote"></span>
                                        <div class="rating"><i class="fa fa-star"></i><i class="fa fa-star"></i><i
                                                class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
                                        </div>
                                    </div>
                                    <div class="text">This is due to their excellent service, competitive pricing and
                                        customer support. It’s refresing to get such a personal touch. Duis aute lorem ipsum
                                        is simply free text available in the market reprehen.</div>
                                    <div class="info-box">
                                        <h4 class="name">Mike Hardson</h4>
                                        <span class="designation">Senior Designer</span>
                                    </div>
                                </div>
                                <div class="image-column col-lg-6 col-md-12">
                                    <figure class="image"><img src="/images/resource/testimonial-1.png" alt=""></figure>
                                </div>
                            </div>
                        </swiper-slide>

                        <!-- Testimonial Block Two -->
                        <swiper-slide class="testimonial-block swiper-slide">
                            <div class="row">
                                <div class="content-column col-lg-6 col-md-12">
                                    <div class="icon-box">
                                        <span class="icon icon-quote"></span>
                                        <div class="rating"><i class="fa fa-star"></i><i class="fa fa-star"></i><i
                                                class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
                                        </div>
                                    </div>
                                    <div class="text">competitive pricing and customer support. It’s refresing to get such a
                                        personal touch. Duis aute lorem ipsum is simply free text available in the market
                                        reprehen. This is due to their excellent service,</div>
                                    <div class="info-box">
                                        <h4 class="name">Jessica Brown</h4>
                                        <span class="designation">Senior Designer</span>
                                    </div>
                                </div>
                                <div class="image-column col-lg-6 col-md-12">
                                    <figure class="image"><img src="/images/resource/testimonial-1.png" alt=""></figure>
                                </div>
                            </div>
                        </swiper-slide>

                        <!-- Testimonial Block Two -->
                        <swiper-slide class="testimonial-block swiper-slide">
                            <div class="row">
                                <div class="content-column col-lg-6 col-md-12">
                                    <div class="icon-box">
                                        <span class="icon icon-quote"></span>
                                        <div class="rating"><i class="fa fa-star"></i><i class="fa fa-star"></i><i
                                                class="fa fa-star"></i><i class="fa fa-star"></i><i class="fa fa-star"></i>
                                        </div>
                                    </div>
                                    <div class="text">Simply free text available in the market reprehen. This is due to
                                        their excellent service, competitive pricing and customer support. It’s refresing to
                                        get such a personal touch. Duis aute lorem ipsum is </div>
                                    <div class="info-box">
                                        <h4 class="name">michale smith</h4>
                                        <span class="designation">Senior Designer</span>
                                    </div>
                                </div>
                                <div class="image-column col-lg-6 col-md-12">
                                    <figure class="image"><img src="/images/resource/testimonial-1.png" alt=""></figure>
                                </div>
                            </div>
                        </swiper-slide>


                        <!-- Add Pagination -->
                        <div class="testimonial-pagination"></div>
                    </swiper>
                </div>

                <!-- Testimonial Thumbs -->
                <!-- <div class="swiper-container testimonial-thumbs">
                    <div class="swiper-wrapper">
                        <div class="swiper-slide testimonial-thumb">
                            <figure class="image"><img src="/images/resource/testi-thumb-2.jpg" alt=""></figure>
                        </div>
                        <div class="swiper-slide testimonial-thumb">
                            <figure class="image"><img src="/images/resource/testi-thumb-1.jpg" alt=""></figure>
                        </div>
                        <div class="swiper-slide testimonial-thumb">
                            <figure class="image"><img src="/images/resource/testi-thumb-3.jpg" alt=""></figure>
                        </div>
                    </div>
                </div> -->
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