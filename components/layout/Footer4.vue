<template>
  <footer class="app-4 main-footer-app-5" style="background: #102E7A;">
    <!--Widgets Section-->
    <div class="widgets-section">
      <div class="auto-container">
        <div class="row">
          <!--Footer Column-->
          <div class="footer-column col-lg-4 col-md-6">
            <div class="footer-widget about-widget">
              <h3 class="widget-title">About</h3>
              <div class="text">Desires to obtain pain of itself, because it is pain, but occasionally circumstances.</div>
              <div class="btn-box d-flex">
                <NuxtLink to="tel:+92(8800)9806" class="info-btn">
                  <i class="icon fa fa-phone"></i>
                  <small>Email Address</small><br> info@domain.com
                </NuxtLink>
              </div>
            </div>
          </div>
          <!--Footer Column-->
          <div class="footer-column col-lg-4 col-md-6">
            <div class="footer-widget">
              <h3 class="widget-title">Explore</h3>
              <div class="d-flex">
                <ul class="user-links">
                  <li><NuxtLink to="#">About Company</NuxtLink></li>
                  <li><NuxtLink to="#">Meet the Team</NuxtLink></li>
                  <li><NuxtLink to="#">News & Media</NuxtLink></li>
                </ul>
                <ul class="user-links">
                  <li><NuxtLink to="#">About Company</NuxtLink></li>
                  <li><NuxtLink to="#">Meet the Team</NuxtLink></li>
                </ul>
              </div>
            </div>
          </div>
          <!--Footer Column-->
          <div class="footer-column col-lg-4 col-md-6">
            <div class="footer-widget">
              <h3 class="widget-title">Contact</h3>
              <div class="widget-content">
                <div class="subscribe-form pt-0">
                  <p class="text-white mb-30">Subscribe to our newsletter for discount and more</p>
                  <form method="post" action="#">
                    <div class="form-group">
                      <input type="email" name="email" class="email" value="" placeholder="Email Address" required="">
                      <button type="button" class="theme-btn btn-style-one text-white"><span class="btn-title"><i class="far fa-paper-plane"></i></span></button>
                    </div>
                  </form>
                  <ul class="social-icon-two">
                    <li><NuxtLink to="#" class="icon"><i class="fab fa-twitter"></i></NuxtLink></li>
                    <li><NuxtLink to="#" class="icon"><i class="fab fa-facebook"></i></NuxtLink></li>
                    <li><NuxtLink to="#" class="icon"><i class="fab fa-pinterest"></i></NuxtLink></li>
                    <li><NuxtLink to="#" class="icon"><i class="fab fa-instagram"></i></NuxtLink></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!--Footer Bottom-->
    <div class="footer-bottom">
      <div class="auto-container">
        <div class="inner-container">
          <div class="copyright-text">&copy; Copyright Reserved by  <NuxtLink to="https://kodesolution.com/" style="color: #8c8f94;">kodesolution.com</NuxtLink></div>
        </div>
      </div>
    </div>
  </footer>
</template>