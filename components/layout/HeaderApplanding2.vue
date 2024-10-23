<template>
  <header class="main-header main-footer-app-4 header-style-four" :class="{ 'moblie-search-active': isSearch }">
    <!-- Header Lower -->
    <div class="header-lower">
      <!-- Main box -->
      <div class="main-box">
        <div class="logo-box">
          <div class="logo"><NuxtLink to="/index"><img src="/images/logo.png" alt=""></NuxtLink></div>
        </div>

        <!--Nav Box-->
        <div class="nav-outer">

          <nav class="nav main-menu">
            <ul class="navigation onepage-nav">
              <li v-for="(item, index) in nabvabar" :key="index" @click="handleSinglePageMenu()">
                <NuxtLink class="scroll-to" :to="item.link">
                  <i :class="item.icon"></i> <span>{{ item.name }}</span>
                </NuxtLink>
              </li>
            </ul>
          </nav>
          <!-- Main Menu End-->
        </div>

        <div class="outer-box">
          <NuxtLink to="tel:+92(8800)9806" class="info-btn">
            <i class="icon fa fa-phone"></i>
            <small>Call Anytime</small><br> + 88 ( 9800 ) 6802
          </NuxtLink>

          <!-- Mobile Nav toggler -->
          <div class="mobile-nav-toggler" @click="handleToggled"><span class="icon lnr-icon-bars"></span></div>
        </div>
      </div>
    </div>
    <!-- End Header Lower -->

    <!-- Mobile Menu  -->
    <div class="mobile-menu">
      <div class="menu-backdrop" @click="handleToggled"></div>

      <!--Here Menu Will Come Automatically Via Javascript / Same Menu as in Header-->
      <nav class="menu-box">
        <div class="upper-box">
          <div class="nav-logo"><NuxtLink to="/index"><img src="/images/logo.png" alt="" title=""></NuxtLink></div>
          <div class="close-btn" @click="handleToggled"><i class="icon fa fa-times"></i></div>
        </div>

        <LayoutMobileMenuApp2 />
        <ul class="contact-list-one">
          <li>
            <!-- Contact Info Box -->
            <div class="contact-info-box">
              <i class="icon lnr-icon-phone-handset"></i>
              <span class="title">Call Now</span>
              <NuxtLink to="tel:+92880098670">+92 (8800) - 98670</NuxtLink>
            </div>
          </li>
          <li>
            <!-- Contact Info Box -->
            <div class="contact-info-box">
              <span class="icon lnr-icon-envelope1"></span>
              <span class="title">Send Email</span>
              <NuxtLink to="mailto:help@company.com">help@company.com</NuxtLink>
            </div>
          </li>
          <li>
            <!-- Contact Info Box -->
            <div class="contact-info-box">
              <span class="icon lnr-icon-clock"></span>
              <span class="title">Send Email</span>
              Mon - Sat 8:00 - 6:30, Sunday - CLOSED
            </div>
          </li>
        </ul>


        <ul class="social-links">
          <li><NuxtLink to="#"><i class="fab fa-twitter"></i></NuxtLink></li>
          <li><NuxtLink to="#"><i class="fab fa-facebook-f"></i></NuxtLink></li>
          <li><NuxtLink to="#"><i class="fab fa-pinterest"></i></NuxtLink></li>
          <li><NuxtLink to="#"><i class="fab fa-instagram"></i></NuxtLink></li>
        </ul>
      </nav>
    </div><!-- End Mobile Menu -->

    <!-- Header Search -->
    <div class="search-popup">
      <span class="search-back-drop"></span>
      <button class="close-search" @click="handleSearch"><span class="fa fa-times"></span></button>

      <div class="search-inner">
        <form method="post" action="index">
          <div class="form-group">
            <input type="search" name="search-field" value="" placeholder="Search..." required="">
            <button type="submit"><i class="fa fa-search"></i></button>
          </div>
        </form>
      </div>
    </div>
    <!-- End Header Search -->

    <!-- Sticky Header  -->
    <div class="sticky-header" :class="{ 'fixed-header animated slideInDown': scroll }">
      <div class="auto-container">
        <div class="inner-container">
          <!--Logo-->
          <div class="logo">
            <NuxtLink to="/index"><img src="/images/logo-2.png" alt=""></NuxtLink>
          </div>

          <!--Right Col-->
          <div class="nav-outer">
            <!-- Main Menu -->
            <nav class="main-menu">
              <ul class="navigation onepage-nav">
                <li v-for="(item, index) in nabvabar" :key="index" @click="handleSinglePageMenu()">
                  <NuxtLink class="scroll-to" :to="item.link">
                    <i :class="item.icon"></i> <span>{{ item.name }}</span>
                  </NuxtLink>
                </li>
              </ul>
            </nav><!-- Main Menu End-->

            <!--Mobile Navigation Toggler-->
            <div class="mobile-nav-toggler" @click="handleToggled"><span class="icon lnr-icon-bars"></span>
            </div>
          </div>
        </div>
      </div>
    </div><!-- End Sticky Menu -->
  </header>
</template>

<script setup>
import { onMounted, onUnmounted, ref } from 'vue'
const scroll = ref(false)
const handleScroll = () => {
  const scrollCheck = window.scrollY > 100
  if (scrollCheck !== scroll.value) {
    scroll.value = scrollCheck
  }
}

onMounted(() => {
  document.addEventListener("scroll", handleScroll)
})
onUnmounted(() => {
  document.removeEventListener("scroll", handleScroll)
})


const isToggled = ref(false)
const handleToggled = () => {
  isToggled.value = !isToggled.value
  document.body.classList.toggle("mobile-menu-visible", isToggled.value)
}
const isSearch = ref(false)
const handleSearch = () => {
  isSearch.value = !isSearch.value
}









const singleMenu = ref(false)
// nabvar 
const nabvabar = reactive([
  {
    id: 1,
    name: 'Home',
    link: '#home',
    icon: 'las la-home',
  },
  {
    id: 2,
    name: 'About',
    link: '#about',
    icon: 'lar la-user',
  },
  {
    id: 3,
    name: 'Services',
    link: '#services',
    icon: 'las la-stream',
  },
  {
    id: 4,
    name: 'Pricing',
    link: '#pricing',
    icon: 'las la-envelope',
  },
  {
    id: 5,
    name: 'Contact',
    link: '#contact',
    icon: 'las la-envelope',
  },
])
const handleSinglePageMenu = () => {
  singleMenu.value = !singleMenu.value
}
</script>
