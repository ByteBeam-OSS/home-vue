

<template>
    <section class="faqs-section style-two">
        <div class="auto-container">
            <div class="row">
                <!-- FAQ Column -->
                <div class="faq-column col-xl-6 col-lg-12 col-md-12 order-4">
                    <div class="inner-column">
                        <div class="sec-title">
                            <span class="sub-title">Questions & answers</span>
                            <h2>See Frequently Asked Questions</h2>
                        </div>

                        <ul class="accordion-box wow fadeInRight">
                            <!--Block-->
                            <li class="accordion block" :class="{ 'active-block': isActive.key === 1}">
                                <div class="acc-btn" :class="{ 'active': isActive.key === 1}" @click="handleClick(1)">Is my technology allowed on tech?
                                    <div class="icon fa fa-plus"></div>
                                </div>
                                <div class="acc-content" :class="{ 'current': isActive.key === 1}">
                                    <div class="content">
                                        <div class="text">There are many variations of passages the majority have suffered
                                            alteration in some fo
                                            injected humour, or randomised words believable.</div>
                                    </div>
                                </div>
                            </li>
                            <!--Block-->
                            <li class="accordion block" :class="{ 'active-block': isActive.key === 2}">
                                <div class="acc-btn" :class="{ 'active': isActive.key === 2}" @click="handleClick(2)">How to soft launch your business?
                                    <div class="icon fa fa-plus"></div>
                                </div>
                                <div class="acc-content" :class="{ 'current': isActive.key === 2}">
                                    <div class="content">
                                        <div class="text">There are many variations of passages the majority have suffered
                                            alteration in some fo injected humour, or randomised words believable.</div>
                                    </div>
                                </div>
                            </li>
                            <!--Block-->
                            <li class="accordion block" :class="{ 'active-block': isActive.key === 3}">
                                <div class="acc-btn" :class="{ 'active': isActive.key === 3}" @click="handleClick(3)">How to turn visitors into contributors
                                    <div class="icon fa fa-plus"></div>
                                </div>
                                <div class="acc-content" :class="{ 'current': isActive.key === 3}">
                                    <div class="content">
                                        <div class="text">There are many variations of passages the majority have suffered
                                            alteration in some fo injected humour, or randomised words believable.</div>
                                    </div>
                                </div>
                            </li>
                            <!--Block-->
                            <li class="accordion block" :class="{ 'active-block': isActive.key === 4}">
                                <div class="acc-btn" :class="{ 'active': isActive.key === 4}" @click="handleClick(4)">How can i find my solutions?
                                    <div class="icon fa fa-plus"></div>
                                </div>
                                <div class="acc-content" :class="{ 'current': isActive.key === 4}">
                                    <div class="content">
                                        <div class="text">There are many variations of passages the majority have suffered
                                            alteration in some fo injected humour, or randomised words believable.</div>
                                    </div>
                                </div>
                            </li>
                        </ul>
                    </div>
                </div>

                <!-- image Column -->
                <div class="image-column col-xl-6 col-lg-12 col-md-12">
                    <div class="inner-column">
                        <figure class="image"><img src="/images/resource/faq.jpg" alt=""></figure>
                        <div class="info-box">
                            <div class="inner">
                                <span class="icon flaticon-business-063-diamond"></span>
                                <h3 class="title">Trusted IT Solution<br> & Service Business Agency</h3>
                            </div>
                        </div>
                    </div>
                </div>
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
}
</script>
