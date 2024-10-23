<template>
  <section id="contact" class="app-4 contact-section-app" style="padding: 120px 0;">
    <div class="auto-container">
      <div class="row">
        <!-- Info Column -->
        <div class="info-column col-lg-6">
          <div class="inner-column wow fadeInRight">
            <div class="sec-title-app-no-subborder">
              <div class="sub-title">Get in Touch</div>
              <h2>Don’t Hesitate to contact with us for any kind of information</h2>
            </div>
            <div class="text">Call us for imiditate support this number</div>
            <div class="text" style="font-size: 30px; color: #000;"><a href="tel:+999000111222" style="font-weight: 700;">+999 000 111 222</a></div>
          </div>
        </div>
        <!-- Form Column -->
        <div class="form-column col-lg-6">
          <div class="inner-column">
            <!-- Contact Form -->
            <div class="contact-form-app style-two wow fadeInLeft">
              <!--Contact Form-->
              <form method="post" action="get" id="contact-form">
                <div class="row">
                  <div class="form-group col-md-6">
                    <input type="text" name="full_name" placeholder="Your Name" required>
                  </div>
                  <div class="form-group col-md-6">
                    <input type="email" name="Email" placeholder="Email Address" required>
                  </div>
                  <div class="form-group col-md-6">
                    <input type="text" name="Phone" placeholder="Phone Number" required>
                  </div>
                  <div class="form-group col-md-6">
                    <input type="text" name="subject" placeholder="Subject" required>
                  </div>
                  <div class="form-group col-lg-12">
                    <textarea name="message" placeholder="Write Message" required></textarea>
                  </div>
                  <div class="form-group col-lg-12">
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
