<template>
    <!-- Hero Section Begin -->
    <section class="hero-section">
        <carousel class="hero-items" :items="1" :nav="false" :autoplay="true">
            <div class="single-hero-items set-bg" style="background-image: url('/img/hero_cookies-1.jpg'">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>Bag,kids</span>
                            <h1 style="color:#ffffff">Black friday</h1>
                            <p style="color:#ffffff">
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore
                            </p>
                            <a href="https://bit.ly/32bWdpL" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </div>
             <div class="single-hero-items set-bg" style="background-image: url('/img/hero_cookies-2.jpg'">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>Bag,kids</span>
                            <h1>Black friday</h1>
                            <p>
                                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </div>
        </carousel>
    </section>
    <!-- Hero Section End -->
</template>

<script>
import carousel from 'vue-owl-carousel';
export default {
    name: "HeroQiow",
    components: {
        carousel
    }
};
</script>