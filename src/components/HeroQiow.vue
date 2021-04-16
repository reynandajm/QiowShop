<template>
    <!-- Hero Section Begin -->
    <section class="hero-section">
        <carousel class="hero-items" :items="1" :nav="false" :autoplay="true">
            <div class="single-hero-items set-bg" style="background-image: url('/img/hero_cookies-1.jpg'">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>Kue Kering</span>
                            <h1 style="color:#ffffff">Promo Lebaran</h1>
                            <p style="color:#ffffff">
                                mau ngemil karena takut gemuk? Tenang. Qiow Cookies sudah terbukti rendah kalori, enak, dan ramah dikantong
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
                            <span>Kue Kering</span>
                            <h1>Promo Lebaran</h1>
                            <p>
                               mau ngemil karena takut gemuk? Tenang. Qiow Cookies sudah terbukti rendah kalori, enak, dan ramah dikantong
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