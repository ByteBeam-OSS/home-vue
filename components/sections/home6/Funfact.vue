<template>
  <!-- Contact Section -->
  <section class="contact-section-four layout_6 pt-0">
    <div class="auto-container">
      <!-- Fact Counter -->
      <div class="fact-counter">
        <div class="row">
          <!-- Counter block-->
          <div class="counter-block-three col-lg-3 col-md-6 wow fadeInUp">
            <div class="inner">
              <div class="count-box"><ElementsCounterUp :end="4520"/>0</div>
              <h6 class="counter-title">Project completed</h6>
            </div>
          </div>
          <!--Counter block-->
          <div class="counter-block-three col-lg-3 col-md-6 wow fadeInUp" data-wow-delay="300ms">
            <div class="inner">
              <div class="count-box"><ElementsCounterUp :end="325"/>0</div>
              <h6 class="counter-title">IT specialists</h6>
            </div>
          </div>
          <!--Counter block-->
          <div class="counter-block-three col-lg-3 col-md-6 wow fadeInUp" data-wow-delay="600ms">
            <div class="inner">
              <div class="count-box"><ElementsCounterUp :end="1357"/>0</div>
              <h6 class="counter-title">Satisfied clients</h6>
            </div>
          </div>
          <!--Counter block-->
          <div class="counter-block-three col-lg-3 col-md-6 wow fadeInUp" data-wow-delay="900ms">
            <div class="inner">
              <div class="count-box"><ElementsCounterUp :end="238"/>0</div>
              <h6 class="counter-title">Smart solutions</h6>
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <!-- Info Column -->
        <div class="info-column col-lg-7">
          <div class="inner-column wow fadeInRight">
            <div class="title-box">
              <h3 class="title">Best IT Technology <br>Services you can Trust</h3>
            </div>
            <div class="our-values">
              <figure class="image"><img src="/images/resource/our-value.jpg" alt=""></figure>
              <div class="content">
                <h5 class="title">Manage Tech Services</h5>
                <div class="text">Web designing in a powerful way of just not an only professions, however, in a passion for our Company. We have to a tendency to believe the idea that smart looking</div>
              </div>
            </div>
            <div class="info-box">
              <figure class="image"><img src="/images/resource/our-value-2.jpg" alt=""></figure>
              <!-- Counter block-->
              <div class="counter-block-two">
                <div class="count-box"><ElementsCounterUp :end="4520" />0</div>
                <h6 class="counter-title">Clients worldwide took Professional IT services</h6>
              </div>
            </div>
          </div>
        </div>

        <!-- Form Column -->
        <div class="form-column col-xl-5 col-lg-6">
          <div class="inner-column">
            <!-- Contact Form -->
            <div class="contact-form light wow fadeInLeft">
              <div class="title-box">
                <span class="sub-title">Contact us</span>
                <h3>Get a Free Quote</h3>
                <p>There are many variations of passages</p>
              </div>
              <!--Contact Form-->
              <form method="post" action="get" id="contact-form">
                <div class="form-group">
                  <input type="text" name="full_name" placeholder="Your Name" required>
                </div>
                <div class="form-group">
                  <input type="text" name="Email" placeholder="Email Address" required>
                </div>
                <div class="form-group">
                  <input type="text" name="Phone" placeholder="Phone Number" required>
                </div>
                <div class="form-group">
                  <textarea name="message" placeholder="Write a Message" required></textarea>
                </div>
                <div class="form-group">
                  <button class="theme-btn btn-style-one" type="submit" name="submit-form"><span class="btn-title">Send a m essage</span></button>
                </div>
              </form>
            </div>
            <!--End Contact Form -->
          </div>
        </div>
      </div>
    </div>
  </section>
  <!--End Contact Section -->
</template>