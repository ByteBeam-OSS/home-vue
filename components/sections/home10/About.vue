<template>
  <section class="about-section-layout-10">
    <div class="auto-container">
      <div class="row">
        <div class="content-column offset-lg-1 col-xl-6 col-lg-7 order-2 wow fadeInRight" data-wow-delay="600ms">
          <div class="inner-column">
            <div class="sec-title">
              <span class="sub-title">About Our Company</span>
              <h2>Best IT Technology Services you can Trust</h2>
              <div class="text">Web designing in a powerful way of just not an only professions, however, in a passion for our Company. We have to a
              tendency to believe the idea that smart looking of any website is the first impression on visitors.</div>
            </div>
            <div class="content-box">
              <div class="row">
                <div class="about-block-layout-9 col-md-6">
                  <h5 class="title"><i class="icon flaticon-business-020-hierarchy"></i> Expert Team Members </h5>
                </div>
                <div class="about-block-layout-9 col-md-6">
                  <h5 class="title"><i class="icon flaticon-business-002-graph"></i> Manage Tech Services </h5>
                </div>
              </div>  
              <div class="text">There are many of Ipsum but the have Aliq is notm hendr erit a augue insu image pellen simply free text</div>
              <div class="btn-box d-flex">
                <NuxtLink to="page-about" class="theme-btn btn-style-one"><span class="btn-title">Discover more</span></NuxtLink>
                <NuxtLink to="tel:+92(8800)9806" class="info-btn">
                  <i class="icon fa fa-phone"></i>
                  <small>Call Anytime</small><br> 92 666 888 000
                </NuxtLink>
              </div>
            </div>
          </div>
        </div>
        <!-- Image Column -->
        <div class="image-column col-xl-5 col-lg-5">
          <div class="inner-column">
            <div class="video_about_10">
              <NuxtLink @click="openVideo" class="play-btn lightbox-image" data-fancybox="gallery" data-caption=""><i class="icon fa fa-play" aria-hidden="true"></i><span class="ripple"></span></NuxtLink>
              <figure class="image-1 overlay-anim wow fadeInUp"><img src="/images/layout_10/project1-600x800.jpg" alt="">
              </figure>
              <figure class="image-10 overlay-anim wow fadeInRight"><img src="/images/layout_10/service5.jpg" alt="">
              </figure>
            </div>
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