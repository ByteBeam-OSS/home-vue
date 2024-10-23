<template>
  <ul class="navigation">
    <li class="current dropdown"><NuxtLink to="/">Home</NuxtLink>
      <ul>
        <li><NuxtLink to="/">Home Layout 1</NuxtLink></li>
        <li><NuxtLink to="/index-2">Home Layout 2</NuxtLink></li>
        <li><NuxtLink to="/index-3">Home Layout 3</NuxtLink></li>
        <li><NuxtLink to="/index-4">Home Layout 4</NuxtLink></li>
        <li><NuxtLink to="/index-5">Home Layout 5</NuxtLink></li>
        <li class="dropdown"><NuxtLink to="/">More Home</NuxtLink>
          <ul>
            <li><NuxtLink to="/index-6">Home Layout 6</NuxtLink></li>
            <li><NuxtLink to="/index-7">Home Layout 7</NuxtLink></li>
            <li><NuxtLink to="/index-8">Home Layout 8</NuxtLink></li>
            <li><NuxtLink to="/index-9">Home Layout 9</NuxtLink></li>
            <li><NuxtLink to="/index-10">Home Layout 10</NuxtLink></li>
          </ul>
        </li>
        <li class="dropdown"><NuxtLink to="/">App Landing</NuxtLink>
          <ul>
            <li><NuxtLink to="/app-landing">App Landing 1</NuxtLink></li>
            <li><NuxtLink to="/app-landing2">App Landing 2</NuxtLink></li>
            <li><NuxtLink to="/app-landing3">App Landing 3</NuxtLink></li>
            <li><NuxtLink to="/app-landing4">App Landing 4</NuxtLink></li>
            <li><NuxtLink to="/app-landing5">App Landing 5</NuxtLink></li>
          </ul>
        </li>
        <li class="dropdown"><NuxtLink to="/">Single Page</NuxtLink>
          <ul>
            <li><NuxtLink to="/single-1">Single Page 1</NuxtLink></li>
          </ul>
        </li>
      </ul>
    </li>
    <li class="dropdown"><NuxtLink to="/">Pages</NuxtLink>
      <ul>
        <li><NuxtLink to="/page-about">About</NuxtLink></li>
        <li class="dropdown"><NuxtLink to="/page-projects">Projects</NuxtLink>
          <ul>
            <li><NuxtLink to="/page-projects">Projects</NuxtLink></li>
            <li><NuxtLink to="/page-project-details">Projects Details</NuxtLink></li>
          </ul>
        </li>
        <li class="dropdown"><NuxtLink to="/">Team</NuxtLink>
          <ul>
            <li><NuxtLink to="/page-team">Team</NuxtLink></li>
            <li><NuxtLink to="/page-team-details">Team Details</NuxtLink></li>
          </ul>
        </li>
      </ul>
    </li>
    <li class="dropdown"><NuxtLink to="/page-services">Services</NuxtLink>
      <ul>
        <li><NuxtLink to="/page-services">Services</NuxtLink></li>
        <li><NuxtLink to="/page-service-details">Service Details</NuxtLink></li>
      </ul>
    </li>
    <li class="dropdown"><NuxtLink to="/news-grid">News</NuxtLink>
      <ul>
        <li><NuxtLink to="/news-grid">News</NuxtLink></li>
        <li><NuxtLink to="/news-details">News Details</NuxtLink></li>
      </ul>
    </li>
    <li><NuxtLink to="/page-contact">Contact</NuxtLink></li>
  </ul>
</template>