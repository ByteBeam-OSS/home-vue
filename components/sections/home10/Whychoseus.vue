<template>
  <section class="why-choose-us-ten">
    <div class="auto-container">
      <div class="row">
        <div class="content-column col-xl-5 col-lg-7 col-md-12 col-sm-12 wow fadeInLeft" data-wow-delay="600ms">
          <div class="inner-column">
            <div class="sec-title">
              <span class="sub-title">why choose our company</span>
              <h2>Why Choose Our IT Services</h2>
              <div class="text">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur</div>
            </div>
            <div class="content-box">
              <div class="about-block-layout-10">
                <i class="icon flaticon-business-018-startup"></i>
                <h5 class="title">Affordable Service Prices</h5>
                <div class="text">We’ve designed a culture that allows our stewards to assimilate</div>
              </div>
              <div class="about-block-layout-10">
                <i class="icon flaticon-business-012-startup"></i>
                <h5 class="title">Internal Networking</h5>
                <div class="text">We’ve designed a culture that allows our stewards to assimilate.</div>
              </div>
            </div>
          </div>
        </div>
        <!-- Image Column -->
        <div class="image-column col-xl-7 col-lg-5 col-md-12 col-sm-12">
          <div class="inner-column wow fadeInRight">
            <figure class="image overlay-anim">
              <img src="/images/layout_10/bg2.jpg" alt="">
              <div class="video-box video-box-10 wow fadeInUp">
                <div class="content">
            <NuxtLink @click="openVideo" class="play-now-two lightbox-image" data-fancybox="gallery" data-caption=""><i class="icon fa fa-play"></i><span class="ripple"></span></NuxtLink>
                </div>
              </div>
            </figure>
          </div>
        </div>
      </div>
    </div>
  </section>
  <modal-video :channel="videoChannel" :videoId="videoId" v-model:isOpen="videoIsOpen" />
</template>
<script>
  import ModalVideo from '../components/elements/ModalVideo.vue'
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
    },
  }
</script>