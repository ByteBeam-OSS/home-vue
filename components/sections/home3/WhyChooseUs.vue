<template>
    <section class="why-choose-us-two pt-0">
        <div class="auto-container">
            <div class="row">
                <div class="content-column col-xl-6 col-lg-7 col-md-12 col-sm-12 wow fadeInLeft" data-wow-delay="600ms">
                    <div class="inner-column">
                        <div class="sec-title">
                            <span class="sub-title">why choose our company</span>
                            <h2>Why you Should Choose Our Services?</h2>
                            <div class="text">There are many variations of passages of but the majority have in some form,
                                by injected humou or words which don't look even slightly believable of but the majority
                                have suffered.</div>
                        </div>
                        <div class="row">
                            <div class="col-lg-6 col-md-6 col-sm-12">
                                <div class="info-box">
                                    <i class="icon fa fa-check-circle"></i>
                                    <h6 class="title">Integer et massa sit</h6>
                                </div>
                            </div>
                            <div class="col-lg-6 col-md-6 col-sm-12">
                                <div class="info-box">
                                    <i class="icon fa fa-check-circle"></i>
                                    <h6 class="title">Integer et massa sit</h6>
                                </div>
                            </div>
                        </div>
                        <!--Skills-->
                        <div class="skills">
                            <!--Skill Item-->
                            <div class="skill-item">
                                <div class="skill-header">
                                    <h6 class="skill-title">Technology</h6>
                                </div>
                                <div class="skill-bar">
                                    <div class="bar-inner">
                                        <div class="bar progress-line" data-width="86" style="width: 77%;">
                                            <div class="skill-percentage">
                                                <div class="count-box">
                                                    <ElementsCounterUp :end="86" /> %
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>

                            <!--Skill Item-->
                            <div class="skill-item">
                                <div class="skill-header">
                                    <h6 class="skill-title">Solutions</h6>
                                </div>
                                <div class="skill-bar">
                                    <div class="bar-inner">
                                        <div class="bar progress-line" data-width="77" style="width: 77%;">
                                            <div class="skill-percentage">
                                                <div class="count-box">
                                                    <ElementsCounterUp :end="86" /> %
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Image Column -->
                <div class="image-column col-xl-6 col-lg-5 col-md-12 col-sm-12">
                  <div class="image-box wow fadeInRight">
                    <figure class="image overlay-anim">
                      <img src="/images/resource/why-us-3.jpg" alt="">
                      <NuxtLink @click="openVideo" class="play-btn lightbox-image" data-fancybox="gallery" data-caption=""><i class="icon fa fa-play" aria-hidden="true"></i></NuxtLink>
                    </figure>
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