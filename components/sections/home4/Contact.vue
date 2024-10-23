<template>
    <section class="contact-section-three pull-up">
		<div class="auto-container">
			<div class="row">
				<!-- Info Column -->
				<div class="info-column col-lg-6 col-md-12 col-sm-12 order-2">
					<div class="inner-column wow fadeInRight">
						<div class="sec-title light">
							<div class="sub-title">Get in Touch</div>
							<h2>Get a free quote today</h2>
							<div class="text">Web designing in a powerful way of just not an only professions, however, in a passion for our company</div>
						</div>

						<div class="contact-info-box-two">
							<span class="icon fa fa-map-marker-alt"></span>
							<h6 class="title">Visit Us</h6>
							<div class="text">66 Road Broklyn Street, 600 New York, USA</div>
						</div>

						<div class="contact-info-box-two">
							<span class="icon fa fa-envelope"></span>
							<h6 class="title">Email address</h6>
							<div class="text"><NuxtLink to="/mailto:needhelp@company.com">needhelp@company.com</NuxtLink></div>
						</div>

						<div class="contact-info-box-two">
							<span class="icon fa fa-phone"></span>
							<h6 class="title">Call now</h6>
							<div class="text"><NuxtLink to="/tel:+999000111222">+999 000 111 222</NuxtLink></div>
						</div>
					</div>
				</div>

				<!-- Form Column -->
				<div class="form-column col-lg-6 col-md-12 col-sm-12">
					<div class="inner-column">
						<!-- Contact Form -->
						<div class="contact-form-two style-two wow fadeInLeft">
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
										<button class="theme-btn btn-style-one hvr-light" type="submit" name="submit-form"><span class="btn-title">Send a message</span></button>
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