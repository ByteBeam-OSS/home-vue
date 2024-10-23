<template>
  <ul class="navigation onepage-nav">
    <li v-for="(item, index) in nabvabar" :key="index" @click="handleSinglePageMenu()">
      <NuxtLink class="scroll-to" :to="item.link">
        <i :class="item.icon"></i> <span>{{ item.name }}</span>
      </NuxtLink>
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


// Single Page nabvabar Script
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
    name: 'Project',
    link: '#project',
    icon: 'las la-envelope',
  },
  {
    id: 5,
    name: 'Testimonials',
    link: '#testimonials',
    icon: 'las la-envelope',
  },
  {
    id: 6,
    name: 'Contact',
    link: '#contact',
    icon: 'las la-envelope',
  },
  {
    id: 7,
    name: 'News',
    link: '#news',
    icon: 'las la-envelope',
  },
])
const handleSinglePageMenu = () => {
  singleMenu.value = !singleMenu.value
}
</script>

