<template>
  <section id="about" class="fun-fact-section-app pb-0">
    <div class="auto-container">
      <div class="sec-title-app text-center">
        <span class="sub-title">What We Do</span>
        <h2>Overall 35K+ people’s using our apps</h2>
      </div>
      <div class="fact-counter">
        <div class="row">
          <!-- Counter Block Two-->
          <div class="counter-block-two col-lg-4 col-md-6 wow fadeInUp">
            <div class="inner">
              <div class="count-box"><ElementsCounterUp :end="35"/>k+</div>
              <h6 class="counter-title">Global Customer</h6>
            </div>
          </div>

          <!-- Counter Block Two-->
          <div class="counter-block-two col-lg-4 col-md-6 wow fadeInUp" data-wow-delay="300ms">
            <div class="inner">
              <div class="count-box"><ElementsCounterUp :end="326"/></div>
              <h6 class="counter-title">IT specialists</h6>
            </div>
          </div>

          <!-- Counter Block Two-->
          <div class="counter-block-two col-lg-4 col-md-6 wow fadeInUp" data-wow-delay="600ms">
            <div class="inner">
              <div class="count-box"><ElementsCounterUp :end="8600"/></div>
              <h6 class="counter-title">Satisfied clients</h6>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
