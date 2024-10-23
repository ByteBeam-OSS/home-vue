<template>
  <section class="about-section-two layout_8">
    <div class="auto-container">
      <div class="row">
        <div class="content-column col-xl-5 col-lg-6 order-2 wow fadeInRight" data-wow-delay="600ms">
          <div class="inner-column">
            <div class="sec-title">
              <h2>Let’s Build your future today</h2>
            </div>
            <div class="text mb-30">Web designing in a powerful way of just not an only professions, however, in a passion for our Company. We have to a tendency to believe the idea that smart looking</div>

            <ul class="list-style-three">
              <li>Nullam vel orci ac</li>
              <li>Maecenas id libero</li>
              <li>Donec eu arcu non</li>
              <li>Proin mattis purus</li>
            </ul>
            <!--Skills-->
            <div class="skills">
              <!--Skill Item-->
              <div class="skill-item">
                <div class="skill-header">
                  <h6 class="skill-title">Consulting</h6>
                </div>
                <div class="skill-bar">
                  <div class="bar-inner">
                    <div class="bar progress-line" data-width="86" style="width:86%;">
                      <div class="skill-percentage">
                        <div class="count-box"><ElementsCounterUp :end="86"/>%</div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <!--Skill Item-->
              <div class="skill-item">
                <div class="skill-header">
                  <h6 class="skill-title">Technology</h6>
                </div>
                <div class="skill-bar">
                  <div class="bar-inner">
                    <div class="bar progress-line" data-width="77" style="width:77%;">
                      <div class="skill-percentage">
                        <div class="count-box"><ElementsCounterUp :end="77"/>%</div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <!--Skill Item-->
              <div class="skill-item">
                <div class="skill-header">
                  <h6 class="skill-title">Solutions</h6>
                </div>
                <div class="skill-bar">
                  <div class="bar-inner">
                    <div class="bar progress-line" data-width="77" style="width:77%;">
                      <div class="skill-percentage">
                        <div class="count-box"><ElementsCounterUp :end="77"/>%</div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            
            <div class="btm-box">
              <NuxtLink to="/page-about" class="theme-btn btn-style-one"><span class="btn-title">Discover more</span></NuxtLink>
            </div>
          </div>
        </div>

        <!-- Image Column -->
        <div class="image-column col-xl-7 col-lg-6">
          <div class="inner-column wow fadeInLeft">
            <figure class="image-1 overlay-anim wow fadeInUp"><img src="/images/resource/about-4.jpg" alt=""></figure>
            <figure class="image-2 overlay-anim wow fadeInRight"><img src="/images/resource/about-13.jpg" alt=""></figure>
            <div class="experience bounce-y">30+<br>years experience</div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>