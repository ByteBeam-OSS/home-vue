<template>
  <section class="contact-section-four-white app-4 pt-0">
    <div class="elementor-shape elementor-shape-top" data-negative="false">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 100" preserveAspectRatio="none">
        <path class="elementor-shape-fill" opacity="0.33" d="M473,67.3c-203.9,88.3-263.1-34-320.3,0C66,119.1,0,59.7,0,59.7V0h1000v59.7 c0,0-62.1,26.1-94.9,29.3c-32.8,3.3-62.8-12.3-75.8-22.1C806,49.6,745.3,8.7,694.9,4.7S492.4,59,473,67.3z"></path>
        <path class="elementor-shape-fill" opacity="0.66" d="M734,67.3c-45.5,0-77.2-23.2-129.1-39.1c-28.6-8.7-150.3-10.1-254,39.1 s-91.7-34.4-149.2,0C115.7,118.3,0,39.8,0,39.8V0h1000v36.5c0,0-28.2-18.5-92.1-18.5C810.2,18.1,775.7,67.3,734,67.3z"></path>
        <path class="elementor-shape-fill" d="M766.1,28.9c-200-57.5-266,65.5-395.1,19.5C242,1.8,242,5.4,184.8,20.6C128,35.8,132.3,44.9,89.9,52.5C28.6,63.7,0,0,0,0 h1000c0,0-9.9,40.9-83.6,48.1S829.6,47,766.1,28.9z"></path>
      </svg>
    </div>
    <div class="auto-container">
      <!-- Fact Counter -->
      <div class="fact-counter">
        <div class="row">
          <!-- Counter block-->
          <div class="counter-block-three-white col-lg-3 col-md-6 col-sm-12 wow fadeInUp">
            <div class="inner">
              <div class="count-box"><ElementsCounterUp :end="4520"/></div>
              <h6 class="counter-title">Project completed</h6>
            </div>
          </div>

          <!--Counter block-->
          <div class="counter-block-three-white col-lg-3 col-md-6 col-sm-12 wow fadeInUp" data-wow-delay="300ms">
            <div class="inner">
              <div class="count-box"><ElementsCounterUp :end="325"/></div>
              <h6 class="counter-title">IT specialists</h6>
            </div>
          </div>

          <!--Counter block-->
          <div class="counter-block-three-white col-lg-3 col-md-6 col-sm-12 wow fadeInUp" data-wow-delay="600ms">
            <div class="inner">
              <div class="count-box"><ElementsCounterUp :end="1357"/></div>
              <h6 class="counter-title">Satisfied clients</h6>
            </div>
          </div>

          <!--Counter block-->
          <div class="counter-block-three-white col-lg-3 col-md-6 col-sm-12 wow fadeInUp" data-wow-delay="900ms">
            <div class="inner">
              <div class="count-box"><ElementsCounterUp :end="238"/></div>
              <h6 class="counter-title">Smart solutions</h6>
            </div>
          </div>
        </div>
      </div>


      <div class="row">
        <!-- Info Column -->
        <div class="info-column col-lg-7 col-md-12 col-sm-12">
          <div class="inner-column wow fadeInRight">
            <div class="title-box">
              <h3 class="title text-white">Best IT Technology Services you can Trust</h3>
            </div>

            <div class="our-values">
              <figure class="image"><img src="/images/app5/it3.png" alt=""></figure>
              <div class="content">
                <h5 class="title">Manage Tech Services</h5>
                <div class="text">Web designing in a powerful way of just not an only profession showever in a passion for our Company We have to a tendency to believe</div>
                <ul class="list-style-three list-style-color mt-20">
                  <li>The business applications</li>
                  <li>Revolutionary catalysts chang</li>
                  <li>Catalysts for chang seamlessly</li>
                </ul>
              </div>
            </div>
          </div>
        </div>

        <!-- Form Column -->
        <div class="form-column col-lg-5 col-md-12 col-sm-12">
          <div class="inner-column">
            <!-- Contact Form -->
            <div class="contact-form light wow fadeInLeft">
              <div class="title-box">
                <span class="sub-title">Welcome to tech</span>
                <h3 class="title">Get a Free Quote</h3>
                <div class="text">There are many variations of passages</div>
              </div>
              <!--Contact Form-->
              <form method="post" action="get" id="contact-form">
                <div class="form-group">
                  <input type="text" name="full_name" placeholder="Your Name" required>
                </div>

                <div class="form-group">
                  <input type="email" name="Email" placeholder="Email Address" required>
                </div>

                <div class="form-group">
                  <input type="text" name="Phone" placeholder="Phone Number" required>
                </div>

                <div class="form-group">
                  <select class="custom-select">
                    <option value="Product Development">Product Development</option>
                    <option value="UI/UX Designing">UI/UX Designing</option>
                    <option value="Digital Marketing">Digital Marketing</option>
                  </select>
                </div>

                <div class="form-group">
                  <button class="theme-btn btn-style-one btn-style-chnage" type="submit" name="submit-form"><span class="btn-title">Send a message</span></button>
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
