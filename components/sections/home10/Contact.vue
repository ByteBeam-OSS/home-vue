<template>
  <section class="contact-ten-section">
    <div class="auto-container">
      <div class="row">
        <!-- map Column -->
        <div class="map-column col-lg-6">
          <div class="row align-items-center">
            <!-- Title Column -->
            <div class="title-column col-lg-8">
              <div class="inner-column">
                <div class="sec-title">
                  <span class="sub-title">CONTACT US</span>
                  <h2>Need an IT Solution?</h2>
                  <div class="text">Lorem ipsum dolor sit amet, conse ctetur adipisicing elit is simply free text</div>
                </div>
              </div>
            </div>            
            <!-- Title Column -->
            <div class="column col-lg-4">
              <div class="inner-column">
                <div class="icon">
                  <NuxtLink to="#"><i class="fa fa-phone"></i></NuxtLink>
                  <h5>Service Available</h5>
                </div>
              </div>
            </div>
          </div>
          <iframe class="map" src="https://maps.google.com/maps?width=100%25&amp;height=600&amp;hl=en&amp;q=1%20Grafton%20Street,%20Dublin,%20Ireland+(My%20Business%20Name)&amp;t=&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"></iframe>
        </div>
        <!-- Form Column -->
        <div class="form-column col-lg-6">
          <div class="inner-column">
            <!-- Contact Form -->
            <div class="contact-form-10-layout wow fadeInLeft">
              <div class="title-box">
                <h4>Request a quote</h4>
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
                  <button class="theme-btn btn-style-two hvr-light" type="submit" name="submit-form"><span class="btn-title">Send a message</span></button>
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