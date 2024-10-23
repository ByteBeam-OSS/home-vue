<template>
  <section class="video-section">
    <div class="auto-container">
      <div class="outer-box">
        <div class="title-box text-center">
          <h2 class="title">Trusted IT Solution<br> & Service Business Agency</h2>
        </div>
        <div class="video-box wow fadeInUp">
          <figure class="image"><img src="/images/resource/video-img.jpg" alt=""></figure>
          <div class="content">
            <NuxtLink @click="openVideo" class="play-btn lightbox-image" data-fancybox="gallery" data-caption=""><i class="icon fa fa-play" aria-hidden="true"></i></NuxtLink>
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