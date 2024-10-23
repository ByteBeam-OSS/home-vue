

<template>
    <section class="fun-fact-section-two">
		<div class="auto-container">
			<div class="fact-counter">
				<div class="row">
					<!-- Counter Block Two-->
					<div class="counter-block-two col-lg-3 col-md-6 col-sm-12 wow fadeInUp">
						<div class="inner">
							<i class="icon flaticon-business-060-graph"></i>
							<div class="count-box"><ElementsCounterUp :end="4520" /> 
							</div>
							<h6 class="counter-title">Project completed</h6>
						</div>
					</div>

					<!-- Counter Block Two-->
					<div class="counter-block-two col-lg-3 col-md-6 col-sm-12 wow fadeInUp" data-wow-delay="300ms">
						<div class="inner">
							<i class="icon flaticon-business-035-helpline"></i>
							<div class="count-box"><ElementsCounterUp :end="326" /></div>
							<h6 class="counter-title">IT specialists</h6>
						</div>
					</div>

					<!-- Counter Block Two-->
					<div class="counter-block-two col-lg-3 col-md-6 col-sm-12 wow fadeInUp" data-wow-delay="600ms">
						<div class="inner">
							<i class="icon flaticon-business-020-hierarchy"></i>
							<div class="count-box"><ElementsCounterUp :end="8600" />
							</div>
							<h6 class="counter-title">Satisfied clients</h6>
						</div>
					</div>

					<!-- Counter Block Two-->
					<div class="counter-block-two col-lg-3 col-md-6 col-sm-12 wow fadeInUp" data-wow-delay="900ms">
						<div class="inner">
							<i class="icon flaticon-business-048-coin"></i>
							<div class="count-box"><ElementsCounterUp :end="238" /></div>
							<h6 class="counter-title">Smart solutions</h6>
						</div>
					</div>
				</div>
			</div>
		</div>
	</section>
</template>