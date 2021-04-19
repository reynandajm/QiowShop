<template>
    <!-- Women Banner Section Begin -->
    <section class="women-banner">
        <div class="container-fluid">
            <div class="row">
                <div class="col-lg-12 mt-4">
                    <carousel class="product-slider" :items="2" :nav="false" :autoplay="true" :dots="false">
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/cookies/bolasusu_putih.jpg" alt="" />
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Kue Kering</div>
                                <a href="/#/product">
                                    <h5>Kue Bola Susu</h5>
                                </a>
                                <div class="product-price">
                                    Rp.60.000
                                    <span>Rp.65.000</span>
                                </div>
                            </div>
                        </div>
                        <div class="product-item col-">
                            <div class="pi-pic">
                                <img src="img/cookies/salju.jpg" alt="" />
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Kue Kering</div>
                                <a href="#">
                                    <h5>Kue Salju</h5>
                                </a>
                                <div class="product-price">
                                    Rp.60.000
                                    <span>Rp.70.000</span>
                                </div>
                            </div>
                        </div>

                    </carousel>
                </div>
            </div>
        </div>
        <div class="container-fluid">
            <div class="row">
                <div class="col-12 mt-5">
                    <carousel class="product-slider" :items="2" :nav="false" :autoplay="true" :dots="false">
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/cookies/nastar.jpg" alt="" />
                                <!-- <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="product.html">+ Quick View</a></li>
                                </ul> -->
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Kue Kering</div>
                                <a href="#">
                                    <h5>Kue Nastar</h5>
                                </a>
                                <div class="product-price">
                                    Rp.60.000
                                    <span>Rp.65.000</span>
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/cookies/bolasusu_coklat.jpg" alt="" />
                                <!-- <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="#">+ Quick View</a></li>
                                </ul> -->
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Kue Kering</div>
                                <a href="#">
                                    <h5>Kue Bola Coklat</h5>
                                </a>
                                <div class="product-price">
                                    Rp.60.000
                                </div>
                            </div>
                        </div>
                    </carousel>
                </div>
            </div>
        </div>
        <div class="container-fluid">
            <div class="row">
                <div class="col-12 mt-5">
                    <carousel class="product-slider" :items="2" :nav="false" :autoplay="true" :dots="false">
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/cookies/keju.jpg" alt="" />
                                <!-- <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="#">+ Quick View</a></li>
                                </ul> -->   
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Kue Kering</div>
                                <a href="#">
                                    <h5>Kue Keju</h5>
                                </a>
                                <div class="product-price">
                                    Rp.60.000
                                </div>
                            </div>
                        </div>
                        <div class="product-item">
                            <div class="pi-pic">
                                <img src="img/cookies/coklat_kacang.jpg" alt="" />
                                <!-- <ul>
                                    <li class="w-icon active">
                                        <a href="#"><i class="icon_bag_alt"></i></a>
                                    </li>
                                    <li class="quick-view"><a href="#">+ Quick View</a></li>
                                    <li class="w-icon">
                                        <a href="#"><i class="fa fa-random"></i></a>
                                    </li>
                                </ul> -->
                            </div>
                            <div class="pi-text">
                                <div class="catagory-name">Kue Kering</div>
                                <a href="#">
                                    <h5>Coklat Kacang</h5>
                                </a>
                                <div class="product-price">
                                    Rp. 50.000
                                </div>
                            </div>
                        </div>
                    </carousel>
                </div>
            </div>
        </div>
        
    </section>
    <!-- Women Banner Section End -->
</template>

<script>
import carousel from 'vue-owl-carousel';
export default {
    name: "ItemsQiow",
    components: {
        carousel
    }
};
</script>

<style scoped>
.product-item {
    margin-right: 25px;
}
</style>