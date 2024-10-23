
<template>
  <section class="offer-section">
    <div class="auto-container">
      <div class="row">
        <!-- Content Column -->
        <div class="content-column col-lg-6 col-md-12">
          <div class="inner-column">
            <div class="sec-title light">
              <span class="sub-title">Tech management</span>
              <h2>The Best Source for IT Solutions</h2>
              <div class="text">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore
              eu convenient scheduling, account fugiat nulla pariatur.</div>
            </div>
            <div class="info-box">
              <i class="icon flaticon-business-036-idea"></i>
              <h5 class="title">We’re doing the right thing.<br> The right way.</h5>
            </div>
            <ul class="list-style-two">
              <li><i class="fa fa-check-circle"></i> Lorem Ipsum is not simply random text</li>
              <li><i class="fa fa-check-circle"></i> Making this the first true generator on the Internet</li>
              <li><i class="fa fa-check-circle"></i> Various versions have evolved over the years</li>
            </ul>
          </div>
        </div>

        <!-- Content Column -->
        <div class="image-column col-lg-6 col-md-12 col-sm-12">
          <div class="inner-column">
            <div class="image-box">
              <figure class="image"><img src="/images/resource/image-3.jpg" alt=""></figure>
              <div class="caption-box wow slideInRight">
                <div class="icon-box">
                  <NuxtLink @click="openVideo" class="play-now-two lightbox-imagenow" data-fancybox="gallery" data-caption=""><i
                    class="icon fa fa-play" aria-hidden="true"></i><span class="ripple"></span></NuxtLink>
                  </div>
                  <div class="title-box">
                    <h5 class="title">Professional IT technology services you can trust</h5>
                  </div>
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
