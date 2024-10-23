

<template>
    <section class="contact-section">
        <div class="auto-container">
            <div class="row">
                <!-- Image Column -->
                <div class="image-column col-lg-6 col-md-12 col-sm-12 order-4">
                    <div class="inner-column">
					<div class="contact-details__right">
						<div class="sec-title">
							<span class="sub-title">Need any help?</span>
							<h2>Get in touch with us</h2>
							<div class="text">Lorem ipsum is simply free text available dolor sit amet, consectetur notted adipisicing elit sed do eiusmod tempor incididunt simply free ut labore et dolore magna aliqua.</div>
						</div>
						<ul class="list-unstyled contact-details__info">
							<li>
								<div class="icon">
									<span class="lnr-icon-phone-plus"></span>
								</div>
								<div class="text">
									<h6>Have any question?</h6>
                                    <NuxtLink to="tel:980089850"><span>Free</span> +92 (020)-9850</NuxtLink>
								</div>
							</li>
							<li>
								<div class="icon">
									<span class="lnr-icon-envelope1"></span>
								</div>
								<div class="text">
									<h6>Write email</h6>
                                    <NuxtLink to="mailto:needhelp@company.com">needhelp@company.com</NuxtLink>
								</div>
							</li>
							<li>
								<div class="icon">
									<span class="lnr-icon-location"></span>
								</div>
								<div class="text">
									<h6>Visit anytime</h6>
									<span>66 broklyn golden street. New York</span>
								</div>
							</li>
						</ul>
					</div>
                    </div>
                </div>

                <!-- Form Column -->
                <div class="form-column col-lg-6 col-md-12 col-sm-12">
                    <div class="form-bg" style="background-image: url(./images/background/3.jpg)"></div>
                    <div class="inner-column pt-0">
                        <div class="sec-title">
                            <span class="sub-title">Connect with us</span>
                            <h2>Feel free to contact us with any questions.</h2>
                            <div class="text">There are many variations of passages of lorem free market to available, but
                                the majority have alteration in some form, by injected humour, or randomised of ipsum
                                available, but the majority have suffered</div>
                        </div>

                        <!-- Contact Form -->
                        <div class="contact-form-two wow fadeInLeft">
                            <!--Contact Form-->
                            <form method="post" action="get" id="contact-form">
                                <div class="row">
                                    <div class="form-group col-lg-6 col-md-12">
                                        <input type="text" name="full_name" placeholder="Full Name" required>
                                    </div>
                                    <div class="form-group col-lg-6 col-md-12">
                                        <input type="text" name="Email" placeholder="Email Address" required>
                                    </div>
                                    <div class="form-group col-lg-6 col-md-12">
                                        <input type="text" name="Phone" placeholder="Your Phone" required>
                                    </div>
                                    <div class="form-group col-lg-6 col-md-12">
                                        <input type="text" name="Phone" placeholder="Subject" required>
                                    </div>
                                    <div class="form-group col-lg-12 col-md-12">
                                        <button class="theme-btn btn-style-one" type="submit" name="submit-form"><span
                                                class="btn-title">Send a message</span></button>
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