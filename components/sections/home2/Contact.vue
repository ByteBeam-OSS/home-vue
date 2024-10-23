<template>
    <section class="contact-section">
        <div class="auto-container">
            <div class="row">
                <!-- Image Column -->
                <div class="image-column col-lg-6 col-md-12 col-sm-12 order-4">
                    <div class="inner-column">
                        <div class="image-box">
                            <figure class="image"><img src="/images/resource/contact.jpg" alt=""></figure>
                            <div class="info-box">
                                <span class="icon flaticon-business-035-helpline"></span>
                                <span class="sub-title">Calll us and book now</span>
                                <h3 class="title"><NuxtLink to="tel:012333444">012 333 444</NuxtLink></h3>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Form Column -->
                <div class="form-column col-lg-6 col-md-12 col-sm-12">
                    <div class="form-bg" style="background-image: url(./images/background/3.jpg)"></div>
                    <div class="inner-column">
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
                                        <button class="theme-btn btn-style-one" type="submit" name="submit-form"><span class="btn-title">Send a message</span></button>
                                    </div>
                                </div>
                            </form>
                        </div>
                        <!--End Contact Form -->
                    </div>
                </div>
            </div>
        </div>
</section></template>