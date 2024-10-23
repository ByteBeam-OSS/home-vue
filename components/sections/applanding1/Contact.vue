<template>
  <section id="contact" class="contact-section-app">
    <div class="shape">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 100" preserveAspectRatio="none">
        <path opacity="0.33" d="M473,67.3c-203.9,88.3-263.1-34-320.3,0C66,119.1,0,59.7,0,59.7V0h1000v59.7 c0,0-62.1,26.1-94.9,29.3c-32.8,3.3-62.8-12.3-75.8-22.1C806,49.6,745.3,8.7,694.9,4.7S492.4,59,473,67.3z"></path>
        <path opacity="0.66" d="M734,67.3c-45.5,0-77.2-23.2-129.1-39.1c-28.6-8.7-150.3-10.1-254,39.1 s-91.7-34.4-149.2,0C115.7,118.3,0,39.8,0,39.8V0h1000v36.5c0,0-28.2-18.5-92.1-18.5C810.2,18.1,775.7,67.3,734,67.3z"></path>
        <path d="M766.1,28.9c-200-57.5-266,65.5-395.1,19.5C242,1.8,242,5.4,184.8,20.6C128,35.8,132.3,44.9,89.9,52.5C28.6,63.7,0,0,0,0 h1000c0,0-9.9,40.9-83.6,48.1S829.6,47,766.1,28.9z"></path>
      </svg>
    </div>
    <div class="auto-container">
      <div class="row">
        <!-- Info Column -->
        <div class="info-column col-lg-6 col-md-12 col-sm-12 order-2">
          <div class="inner-column wow fadeInRight">
            <div class="sec-title-app">
              <div class="sub-title">Get in Touch</div>
              <h2>Don’t Hesitate to contact with us for any kind of information</h2>
              <div class="text">Call us for imiditate support this number</div>
              <div class="text" style="font-size: 30px; color: #000;"><NuxtLink to="/tel:+999000111222" style="font-weight: 700;">+999 000 111 222</NuxtLink></div>
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