<template>
  <section class="work-section">
    <div class="auto-container">
      <div class="sec-title text-center">
        <span class="sub-title">Tech Management</span>
        <h2>The Best Source for <br> IT Solutions</h2>
      </div>
      <div class="tabs-box work-tabs">
        <!--Tabs Box-->
        <ul class="tab-buttons clearfix">
          <li class="tab-btn" @click="selectTab(0)" :class="{'active-btn': selectedTab === 0}">Gaming</li>
          <li class="tab-btn" @click="selectTab(1)" :class="{'active-btn': selectedTab === 1}">Entertainment</li>
          <li class="tab-btn" @click="selectTab(2)" :class="{'active-btn': selectedTab === 2}">Tech Solution</li>
        </ul>

        <div class="tabs-content">
          <!--Tab-->
          <div class="tab" :class="{ 'active-tab': selectedTab === 0}">
            <div class="row">
              <!-- Content Column -->
              <div class="content-column col-xl-7 col-lg-6 col-md-12 order-2">
                <div class="inner-column">
                  <h3>We Execute Our ideas From The Start to Finish</h3>
                  <div class="text">Web designing in a powerful way of just not an only professions, however, in a passion for our Company.</div>
                  <div class="content-box">
                    <div class="about-block-two">
                      <h5 class="title"><i class="icon fa fa-angle-right"></i> Cloud Based Services</h5>
                      <p class="text">Web designing in a powerful way of just</p>
                    </div>
                    <div class="about-block-two">
                      <h5 class="title"><i class="icon fa fa-angle-right"></i> End to End Solutions</h5>
                      <p class="text">Web designing in a powerful way of just</p>
                    </div>
                  </div>
                </div>
              </div>
              <!-- Image Column -->
              <div class="image-column col-xl-5 col-lg-6 col-md-12">
                <figure class="image overlay-anim"><img src="/images/resource/work-1.jpg" alt=""></figure>
              </div>
            </div>
          </div>

          <!--Tab-->
          <div class="tab" :class="{ 'active-tab': selectedTab === 1}">
            <div class="row">
              <!-- Content Column -->
              <div class="content-column col-xl-7 col-lg-6 col-md-12 order-2">
                <div class="inner-column">
                  <h3>We Execute Our ideas From The Start to Finish</h3>
                  <div class="text">Web designing in a powerful way of just not an only professions, however, in a passion for our Company.</div>
                  <div class="content-box">
                    <div class="about-block-two">
                      <h5 class="title"><i class="icon fa fa-angle-right"></i> Cloud Based Services</h5>
                      <p class="text">Web designing in a powerful way of just</p>
                    </div>
                    <div class="about-block-two">
                      <h5 class="title"><i class="icon fa fa-angle-right"></i> End to End Solutions</h5>
                      <p class="text">Web designing in a powerful way of just</p>
                    </div>
                  </div>
                </div>
              </div>
              <!-- Image Column -->
              <div class="image-column col-xl-5 col-lg-6 col-md-12">
                <figure class="image overlay-anim"><img src="/images/resource/why-us-1.jpg" alt=""></figure>
              </div>
            </div>
          </div>

          <!--Tab-->
          <div class="tab" :class="{ 'active-tab': selectedTab === 2}">
            <div class="row">
              <!-- Content Column -->
              <div class="content-column col-xl-7 col-lg-6 col-md-12 order-2">
                <div class="inner-column">
                  <h3>We Execute Our ideas From The Start to Finish</h3>
                  <div class="text">Web designing in a powerful way of just not an only professions, however, in a passion for our Company.</div>
                  <div class="content-box">
                    <div class="about-block-two">
                      <h5 class="title"><i class="icon fa fa-angle-right"></i> Cloud Based Services
                      </h5>
                      <p class="text">Web designing in a powerful way of just</p>
                    </div>
                    <div class="about-block-two">
                      <h5 class="title"><i class="icon fa fa-angle-right"></i> End to End Solutions
                      </h5>
                      <p class="text">Web designing in a powerful way of just</p>
                    </div>
                  </div>
                </div>
              </div>
              <!-- Image Column -->
              <div class="image-column col-xl-5 col-lg-6 col-md-12">
                <figure class="image overlay-anim"><img src="/images/resource/why-us-4.jpg" alt=""></figure>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default{
  data(){
    return{
      selectedTab: 0,
    }
  },
  methods:{
    selectTab(index){
      this.selectedTab = index
    },
  },
}
</script>