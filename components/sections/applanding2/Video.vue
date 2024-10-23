<template>
  <section class="video-section-app-3">
    <div class="auto-container">
      <div class="outer-box">
        <div class="video-box wow slideInUp">
          <div class="video-box-inner">
            <div class="content">
              <NuxtLink @click="openVideo" class="play-btn lightbox-image"><i class="icon fa fa-play"></i> watch video</NuxtLink>
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
