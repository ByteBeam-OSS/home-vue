

<template>
    <section class="offer-section-three pt-0">
        <div class="auto-container">
            <div class="row">
                <!-- Content Column -->
                <div class="content-column col-lg-6 col-md-12 order-2">
                    <div class="inner-column wow fadeInRight">
                        <div class="sec-title">
                            <span class="sub-title">company benefits</span>
                            <h2>Always Deliver More than you Expected</h2>
                        </div>
                        <div class="info-box">
                            <span class="count">01</span>
                            <h5 class="title">End to End Developement</h5>
                            <div class="text">Sed non odio non elit porttitor tincidunt. Donec fermentum tendency elit sit
                                amet</div>
                        </div>
                        <div class="info-box">
                            <span class="count">02</span>
                            <h5 class="title">Software IT Outsource</h5>
                            <div class="text">Sed non odio non elit porttitor tincidunt. Donec fermentum tendency elit sit
                                amet</div>
                        </div>
                        <div class="info-box">
                            <span class="count">03</span>
                            <h5 class="title">Digital Marketing</h5>
                            <div class="text">Sed non odio non elit porttitor tincidunt. Donec fermentum tendency elit sit
                                amet</div>
                        </div>
                    </div>
                </div>

                <!-- Content Column -->
                <div class="image-column col-lg-6 col-md-12 col-sm-12">
                    <div class="inner-column wow fadeInLeft">
                        <div class="image-box">
                            <figure class="image"><img src="/images/resource/benefits.jpg" alt=""></figure>
                            <div class="video-box">
                                <NuxtLink @click="openVideo" class="play-btn lightbox-image"><i
                                        class="icon fa fa-play"></i></NuxtLink>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
    </div>
</section>
<modal-video :channel="videoChannel" :videoId="videoId" v-model:isOpen="videoIsOpen" />
</template>
<script>
import ModalVideo from '../../components/elements/ModalVideo.vue'
export default {
    components: {
        ModalVideo
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