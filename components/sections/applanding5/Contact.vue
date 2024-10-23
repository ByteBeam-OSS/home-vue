<template>
  <section id="contact" class="contact-section-app-3">
    <div class="auto-container">
      <div class="row">
        <!-- Info Column -->
        <div class="info-column col-lg-6 col-md-12 col-sm-12">
          <div class="inner-column wow fadeInRight">
            <div class="sec-title-app">
              <div class="sub-title">Get in Touch</div>
              <h2>Don’t Hesitate to contact with us for any kind of information</h2>
              <div class="text mt-20">Call us for imiditate support this number</div>
              <div class="text mt-20" style="font-size: 40px"><a href="tel:+999000111222" style="font-weight: 700;">+999 000 111 222</a></div>
            </div>
          </div>
        </div>
        <!-- Form Column -->
        <div class="form-column col-lg-6 col-md-12 col-sm-12">
          <div class="inner-column">
            <!-- Contact Form -->
            <div class="contact-form-app style-two wow fadeInLeft">
              <!--Contact Form-->
              <form method="post" action="get" id="contact-form">
                <div class="row">
                  <div class="form-group col-lg-6 col-md-6 col-sm-12">
                    <input type="text" name="full_name" placeholder="Your Name" required>
                  </div>
                  <div class="form-group col-lg-6 col-md-6 col-sm-12">
                    <input type="email" name="Email" placeholder="Email Address" required>
                  </div>
                  <div class="form-group col-lg-6 col-md-6 col-sm-12">
                    <input type="text" name="Phone" placeholder="Phone Number" required>
                  </div>
                  <div class="form-group col-lg-6 col-md-6 col-sm-12">
                    <input type="text" name="subject" placeholder="Subject" required>
                  </div>
                  <div class="form-group col-lg-12 col-md-12 col-sm-12">
                    <textarea name="message" placeholder="Write Message" required></textarea>
                  </div>
                  <div class="form-group col-lg-12 col-md-12 col-sm-12">
                    <button class="theme-btn btn-style-two hvr-light" type="submit" name="submit-form"><span class="btn-title">Send a message</span></button>
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
