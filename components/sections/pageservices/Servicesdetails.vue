
<template>
	<section class="services-details">
		<div class="container">
			<div class="row">
				<!--Start Services Details Sidebar-->
				<div class="col-xl-4 col-lg-4">
					<div class="service-sidebar">
						<!--Start Services Details Sidebar Single-->
						<div class="sidebar-widget service-sidebar-single">
							<div class="service-sidebar wow fadeInUp"
								data-wow-delay="0.1s" data-wow-duration="1200m">
							    <div class="service-list">
						        <ul>
					            <li><NuxtLink to="/page-service-details" class="current"><i class="fas fa-angle-right"></i><span>Digital Marketing</span></NuxtLink></li>
					            <li><NuxtLink to="/page-service-details"><i class="fas fa-angle-right"></i><span>UI/UX Designing</span></NuxtLink></li>
					            <li><NuxtLink to="/page-service-details"><i class="fas fa-angle-right"></i><span>Product Development</span></NuxtLink></li>
					            <li><NuxtLink to="/page-service-details"><i class="fas fa-angle-right"></i><span>Data Analysis</span></NuxtLink></li>
					            <li><NuxtLink to="/page-service-details"><i class="fas fa-angle-right"></i><span>Security System</span></NuxtLink></li>
					            <li><NuxtLink to="/page-service-details"><i class="fas fa-angle-right"></i><span>Data Visualization</span></NuxtLink></li>
						        </ul>
							    </div>
							</div>
						</div>

						<!--End Services Details Sidebar Single-->
            <div class="sidebar-widget banner-widget">
              <div class="widget-content" style="background-image: url(images/resource/contact.jpg);">
                <div class="shape" style="background-image: url(images/resource/overlay-shape.png);"></div>
                <div class="content-box">
                  <div class="icon-box">
                    <i class="lnr lnr-icon-pie-chart"></i>
                  </div>
                  <h3>Be healthy & eat only fresh</h3>
                  <NuxtLink to="/page-contact" class="theme-btn btn-style-two bg-light"><span class="btn-title text-black"> Contact us</span></NuxtLink>
                </div>
              </div>
            </div>

						<!--Start Services Details Sidebar Single-->
						<div class="sidebar-widget service-sidebar-single mt-5">
							<div class="service-sidebar-single-btn wow fadeInUp"
								data-wow-delay="0.5s" data-wow-duration="1200m">
								<NuxtLink to="/" class="theme-btn btn-style-one d-grid"><span class="btn-title"><span class="fas fa-file-pdf"></span> download pdf file</span></NuxtLink>
							</div>
						</div>
						<!--End Services Details Sidebar Single-->
					</div>
				</div>
				<!--End Services Details Sidebar-->

				<!--Start Services Details Content-->
				<div class="col-xl-8 col-lg-8">
					<div class="services-details__content">
						<img src="/images/resource/service-details.jpg" alt="" />
						<h2 class="mt-4">Service Overview</h2>
						<p>Lorem ipsum is simply free text used by copytyping refreshing. Neque porro est qui dolorem ipsum quia quaed inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Aelltes port lacus quis enim var sed efficitur turpis gilla sed sit amet finibus eros. Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the ndustry standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
						<p>When an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. </p>
						<div class="content mt-40">
							<div class="text">
								<h3>Service Center</h3>
								<p>Lorem ipsum is simply free text used by copytyping refreshing. Neque porro est qui dolorem ipsum quia quaed inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.</p>
							</div>
							<div class="feature-list">
								<div class="row clearfix">
									<div class="col-lg-6 col-md-6 col-sm-12 column">
										<div class="single-item">
											<div class="icon-box"><i class="fas fa-check-circle"></i></div>
											<h6 class="title">Fast home delivery</h6>
										</div>
									</div>
									<div class="col-lg-6 col-md-6 col-sm-12 column">
										<div class="single-item">
											<div class="icon-box"><i class="fas fa-check-circle"></i></div>
											<h6 class="title">Secure Payments</h6>
										</div>
									</div>
									<div class="col-lg-6 col-md-6 col-sm-12 column">
										<div class="single-item">
											<div class="icon-box"><i class="fas fa-check-circle"></i></div>
											<h6 class="title">Delivering best products</h6>
										</div>
									</div>
									<div class="col-lg-6 col-md-6 col-sm-12 column">
										<div class="single-item">
											<div class="icon-box"><i class="fas fa-check-circle"></i></div>
											<h6 class="title">Food Inspections</h6>
										</div>
									</div>
									<div class="col-lg-6 col-md-6 col-sm-12 column">
										<div class="single-item">
											<div class="icon-box"><i class="fas fa-check-circle"></i></div>
											<h6 class="title">Generator Systems</h6>
										</div>
									</div>
									<div class="col-lg-6 col-md-6 col-sm-12 column">
										<div class="single-item">
											<div class="icon-box"><i class="fas fa-check-circle"></i></div>
											<h6 class="title">Assessments</h6>
										</div>
									</div>
								</div>
							</div>
						</div>
						<div class=" mt-25">
							<h3>Frequently Asked Question</h3>
							<p>Lorem ipsum is simply free text used by copytyping refreshing. Neque porro est qui dolorem ipsum quia quaed inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo.</p>
							<ul class="accordion-box wow fadeInRight">
								<!--Block-->
								<li class="accordion block">
									<div class="acc-btn">Is my technology allowed on tech?
										<div class="icon fa fa-plus"></div>
									</div>
									<div class="acc-content">
										<div class="content">
											<div class="text">There are many variations of passages the majority have suffered alteration in some fo injected humour, or randomised words believable.</div>
										</div>
									</div>
								</li>
							</ul>
							<ul class="accordion-box wow fadeInRight">
                            <!--Block-->
                            <li class="accordion block" :class="{ 'active-block': isActive.key === 1}">
                                <div class="acc-btn" :class="{ 'active': isActive.key === 1}" @click="handleClick(1)">How to get free immigration?
                                    <div class="icon fa fa-plus"></div>
                                </div>
                                <div class="acc-content" :class="{ 'current': isActive.key === 1}">
                                    <div class="content">
                                        <div class="text">Sed rhoncus facilisis purus, at accumsan purus sagittis vitae.
                                            Nullam acelit at eros imperdiet. Pellentesque sit.</div>
                                    </div>
                                </div>
                            </li>
                            <!--Block-->
                            <li class="accordion block" :class="{ 'active-block': isActive.key === 2}">
                                <div  class="acc-btn" :class="{ 'active': isActive.key === 2}" @click="handleClick(2)">Which country is good for residents?
                                    <div class="icon fa fa-plus"></div>
                                </div>
                                <div class="acc-content" :class="{ 'current': isActive.key === 2}">
                                    <div class="content">
                                        <div class="text">Sed rhoncus facilisis purus, at accumsan purus sagittis vitae.
                                            Nullam acelit at eros imperdiet. Pellentesque sit.</div>
                                    </div>
                                </div>
                            </li>
                            <!--Block-->
                            <li class="accordion block" :class="{ 'active-block': isActive.key === 3}">
                                <div class="acc-btn" :class="{ 'active': isActive.key === 3}" @click="handleClick(3)">Canada study visa requirements?
                                    <div class="icon fa fa-plus"></div>
                                </div>
                                <div class="acc-content" :class="{ 'current': isActive.key === 3}">
                                    <div class="content">
                                        <div class="text">Sed rhoncus facilisis purus, at accumsan purus sagittis vitae.
                                            Nullam acelit at eros imperdiet. Pellentesque sit.</div>
                                    </div>
                                </div>
                            </li>
                        	</ul>
						</div>
					</div>
				</div>
				<!--End Services Details Content-->
			</div>
		</div>
	</section>
</template>
<script setup>
import { ref } from 'vue'

const isActive = ref({
    status: false,
    key: 1,
})

const handleClick = (key) => {
    if (isActive.value.key === key) {
        isActive.value.status = false
    } else {
        isActive.value.status = true
        isActive.value.key = key
    }
};
</script>
