<template>
  <section id="faq" class="faq-section-app" style="background: #F8F8FE; padding: 120px 0;">
    <div class="auto-container">
      <div class="row">
        <!-- Info Column -->
        <div class="info-column col-lg-6">
          <div class="inner-column wow fadeInRight">
            <div class="sec-title-app">
              <div class="sub-title">Get in Touch</div>
              <h2>Do You Have Any Question</h2>
              <div class="text pb-40">If your company is looking for a way to tap into the digital market for its internal operations or customer facing services, mobile app development is the best way to do it</div>
            </div>
          </div>
        </div>
        <!-- FAQ Column -->
        <div class="faq-column col-lg-6">
          <ul class="accordion-box-app wow fadeInRight">
            <!--Block-->
            <li class="accordion block" :class="{ 'active-block': isActive.key === 1}">
              <div class="acc-btn" :class="{ 'active': isActive.key === 1}" @click="handleClick(1)">Is my technology allowed on tech?
                <div class="icon fa fa-plus"></div>
              </div>
              <div class="acc-content" :class="{ 'current': isActive.key === 1}">
                <div class="content">
                  <div class="text">There are many variations of passages the majority have suffered alteration in some fo injected humour, or randomised words believable.</div>
                </div>
              </div>
            </li>
            <!--Block-->
            <li class="accordion block" :class="{ 'active-block': isActive.key === 2}">
              <div class="acc-btn" :class="{ 'active': isActive.key === 2}" @click="handleClick(2)">How to soft launch your business?
                <div class="icon fa fa-plus"></div>
              </div>
              <div class="acc-content" :class="{ 'current': isActive.key === 2}">
                <div class="content">
                  <div class="text">There are many variations of passages the majority have suffered alteration in some fo injected humour, or randomised words believable.</div>
                </div>
              </div>
            </li>
            <!--Block-->
            <li class="accordion block" :class="{ 'active-block': isActive.key === 3}">
              <div class="acc-btn" :class="{ 'active': isActive.key === 3}" @click="handleClick(3)">How to turn visitors into contributors
                <div class="icon fa fa-plus"></div>
              </div>
              <div class="acc-content" :class="{ 'current': isActive.key === 3}">
                <div class="content">
                  <div class="text">There are many variations of passages the majority have suffered alteration in some fo injected humour, or randomised words believable.</div>
                </div>
              </div>
            </li>
            <!--Block-->
            <li class="accordion block" :class="{ 'active-block': isActive.key === 4}">
              <div class="acc-btn" :class="{ 'active': isActive.key === 4}" @click="handleClick(4)">How can i find my solutions?
                <div class="icon fa fa-plus"></div>
              </div>
              <div class="acc-content" :class="{ 'current': isActive.key === 4}">
                <div class="content">
                  <div class="text">There are many variations of passages the majority have suffered alteration in some fo injected humour, or randomised words believable.</div>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>
<script setup>
import { ref } from 'vue'

const isActive = ref({
  status: false,
  key: 1,
})

const handleClick = (key) => {
  if (isActive.value.key === key) {
    isActive.value.status = false
  } else {
    isActive.value.status = true
    isActive.value.key = key
  }
}
</script>
