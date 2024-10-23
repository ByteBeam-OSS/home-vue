<template>
  <section id="pricing" class="pricing-section pt-0">
    <div class="auto-container">
      <div class="row">
        <!-- Content Column -->
        <div class="content-column col-xl-6">
          <div class="inner-column wow fadeInRight">
            <div class="sec-title">
              <h2 class="text-white">Choose Your Optimal Pricing Plans</h2>
              <p class="text pb-40 text-white">If your company is looking for a way to tap into the digital market for its internal operations or customer facing services, mobile app development is the best way to do it</p>
            </div>
            <div class="tm-pricing-smart-switcher-button round-switch-btn">
              <ul class="switch-buttons">
                <li class="active">
                  <NuxtLink to="javascript:" class="btn-toggle active" data-pricing-trigger data-show="month"><span class="title">Monthly</span></NuxtLink>
                </li>
                <li class="">
                  <NuxtLink to="javascript:" class="btn-toggle" data-pricing-trigger data-show="year"> <span class="title">Yearly</span>
                  <span class="price-offer">20% Off</span>      </NuxtLink>
                </li>
              </ul>
            </div>
          </div>
        </div>

        <!-- Content Column -->
        <div class="pricing-column col-xl-6">
          <div class="inner-column wow fadeInLeft">
            <!-- Pricing Block -->
            <div class="tm-pricing-table pricing-block-app style-two price-padding">
              <div class="inner-box">
                <h4 class="title">Basic Plan</h4>
                <div class="price-box price-normal">
                  <h4 class="price"><sup>$</sup>49</h4>
                  <span class="validaty">/ Monthly</span>
                </div>
                <div class="price-box price-secondary">
                  <h4 class="price"><sup>$</sup>128</h4>
                  <span class="validaty">/ Yearly</span>
                </div>
                <ul class="features">
                  <li>24/7 system monitoring</li>
                  <li>Security management</li>
                  <li>Patch management</li>
                  <li>Remote support</li>
                </ul>
                <div class="btn-box">
                  <NuxtLink to="page-pricing.html" class="theme-btn btn-style-two hvr-light"><span class="btn-title">Choose plan</span></NuxtLink>
                </div>
              </div>
            </div>

            <!-- Pricing Block -->
            <div class="tm-pricing-table pricing-block-app style-two pull-left">
              <div class="inner-box">
                <h4 class="title">Pro Plan</h4>
                <div class="price-box price-normal">
                  <h4 class="price"><sup>$</sup>99</h4>
                  <span class="validaty">/ Monthly</span>
                </div>
                <div class="price-box price-secondary">
                  <h4 class="price"><sup>$</sup>199</h4>
                  <span class="validaty">/ Yearly</span>
                </div>
                <ul class="features">
                  <li>24/7 system monitoring</li>
                  <li>Security management</li>
                  <li>Patch management</li>
                  <li>Remote support</li>
                </ul>
                <div class="btn-box">
                  <NuxtLink to="page-pricing.html" class="theme-btn btn-style-two hvr-light"><span class="btn-title">Choose plan</span></NuxtLink>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
