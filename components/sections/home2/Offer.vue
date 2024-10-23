

<template>
    <section class="offer-section-two">
        <div class="auto-container">
            <div class="row">
                <!-- Content Column -->
                <div class="content-column col-lg-6 col-md-12">
                    <div class="inner-column">
                        <div class="sec-title">
                            <span class="sub-title">Welcome to tech</span>
                            <h2>Your Success with the Best IT Solutions</h2>
                        </div>
                        <div class="info-box">
                            <span class="count">01</span>
                            <div class="text">Lorem Ipsum is simply dummy text of the printing and typesetting industry when
                                an unknown printer.</div>
                        </div>
                        <div class="info-box">
                            <span class="count">02</span>
                            <div class="text">Lorem Ipsum is simply dummy text of the printing and typesetting industry when
                                an unknown printer.
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Content Column -->
                <div class="image-column col-lg-6 col-md-12 col-sm-12">
                    <div class="inner-column">
                        <div class="image-box">
                            <figure class="image"><img src="/images/resource/image-6.jpg" alt=""></figure>
                            <div class="video-box wow fadeIn">
                                <h4 class="title">Watch our video</h4>
                                <img class="arrow-icon" src="/images/icons/icon-arrow.png" alt="">
                                <NuxtLink @click="openVideo" class="play-btn lightbox-image" data-fancybox="gallery" data-caption=""><i class="icon fa fa-play" aria-hidden="true"></i></NuxtLink>
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