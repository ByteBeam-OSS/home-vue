<template>
  <ul class="navigation clearfix">
    <li class="dropdown" :class="{ 'current': isActive.key === 1 }">
      <NuxtLink to="/">Home</NuxtLink>
      <ul :class="{ 'd-block': isActive.key === 1 }">
        <li>
          <NuxtLink to="/">Home Layout 1</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/index-2">Home Layout 2</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/index-3">Home Layout 3</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/index-4">Home Layout 4</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/index-5">Home Layout 5</NuxtLink>
        </li>
      </ul>
      <div class="dropdown-btn" :class="{ 'active': isActive.key === 1 }" @click="handleClick(1)"><i class="fa fa-angle-down"></i></div>
    </li>
    <li>
      <NuxtLink to="/page-about">About</NuxtLink>
    </li>
    <li class="dropdown" :class="{ 'current': isActive.key === 3 }">
      <NuxtLink to="/#">Services</NuxtLink>
      <ul :class="{ 'd-block': isActive.key === 3 }">
        <li>
          <NuxtLink to="/page-services">Services List</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/page-service-details">Service Details</NuxtLink>
        </li>
      </ul>
      <div class="dropdown-btn" :class="{ 'active': isActive.key === 3 }" @click="handleClick(3)"><i class="fa fa-angle-down"></i></div>
    </li>
    <li class="dropdown" :class="{ 'current': isActive.key === 3 }">
      <NuxtLink to="/#">Projects</NuxtLink>
      <ul :class="{ 'd-block': isActive.key === 3 }">
        <li>
          <NuxtLink to="/page-projects">Projects List</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/page-projects-details">Projects Details</NuxtLink>
        </li>
      </ul>
      <div class="dropdown-btn" :class="{ 'active': isActive.key === 3 }" @click="handleClick(3)"><i class="fa fa-angle-down"></i></div>
    </li>
    <li class="dropdown" :class="{ 'current': isActive.key === 5 }">
      <NuxtLink to="/#">News</NuxtLink>
      <ul :class="{ 'd-block': isActive.key === 5 }">
        <li>
          <NuxtLink to="/news-details">News Details</NuxtLink>
        </li>
      </ul>
      <div class="dropdown-btn" :class="{ 'active': isActive.key === 5 }" @click="handleClick(5)"><i class="fa fa-angle-down"></i></div>
    </li>
    <li>
      <NuxtLink to="/page-contact">Contact</NuxtLink>
    </li>
  </ul>
</template>
<script setup>
import { ref } from 'vue'

const isActive = ref({
  status: false,
  key: '',
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

