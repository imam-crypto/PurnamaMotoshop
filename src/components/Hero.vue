<template>
    <!-- Hero Section Begin -->
    <section class="hero-section" >
        <carousel class="hero-items" :items="1" :dots="false" :nav="false" :autoplay="true">
            <div class="single-hero-items set-bg" style="background-image:url('/img/pol1.jpg'); ">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>Helm Race</span>
                            <h1>Festival</h1>
                            <p class="conten">
                              Gunakan Helm Full Aerodinamic Untuk Menunjang Performa Balap
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </div>
             <div class="single-hero-items set-bg" style="background-image:url('/img/mv.jpg')">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>Helm Touring</span>
                            <h1>Weekly</h1>
                            <p class="conten">
                               Gunakan perlindungan kepala saat Toring
                            </p>
                            <a href="#" class="primary-btn">Shop Now</a>
                        </div>
                    </div>
                </div>
            </div>
             <div class="single-hero-items set-bg" style="background-image:url('/img/qf.jpg')">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>Variasi</span>
                            <h1>Daily</h1>
                            <p class="conten">
                                Perlengkapan Variasi Sepeda Motor Anda
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
   name:"Hero",
   components:{
       carousel
   }
}
</script>
<style scoped>
.conten{
    color: #FFFF;
}
</style>