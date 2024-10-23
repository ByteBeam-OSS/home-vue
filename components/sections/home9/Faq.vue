<template>
  <section class="faqs-section-home9">
    <div class="auto-container">
      <div class="row">
        <!-- FAQ Column -->
        <div class="faq-column col-lg-6 order-4">
          <div class="faq-bg" style="background-image: url(./images/icons/pattern-2.jpg)"></div>
          <div class="inner-column">
            <div class="sec-title">
              <span class="sub-title">Questions & answers</span>
              <h2>See Frequently Asked Questions</h2>
            </div>
            <ul class="accordion-box wow fadeInRight">
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
            </ul>
          </div>
        </div>

        <!-- Form Column -->
        <div class="form-column col-lg-6">
          <div class="inner-column">
            <!-- Contact Form -->
            <div class="contact-form-9-layout wow fadeInLeft">
              <div class="title-box">
                <span class="sub-title">Contact us</span>
                <h3>Write Email</h3>
              </div>
              <!--Contact Form-->
              <form method="post" action="get" id="contact-form">
                <div class="row">
                  <div class="form-group col-lg-6 col-md-6 col-sm-12">
                    <input type="text" name="full_name" placeholder="Your Name" required>
                  </div>
                  <div class="form-group col-lg-6 col-md-6 col-sm-12">
                    <input type="text" name="Email" placeholder="Email Address" required>
                  </div>
                  <div class="form-group">
                    <input type="text" name="Phone" placeholder="Phone Number" required>
                  </div>
                  <div class="form-group">
                    <textarea name="message" placeholder="Write a Message" required></textarea>
                  </div>
                  <div class="form-group">
                    <button class="theme-btn btn-style-new-layout bg_4" type="submit" name="submit-form"><span class="btn-title">Send a message</span></button>
                  </div>
                </div>
              </form>
            </div>
            <!--End Contact Form -->
          </div>
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
