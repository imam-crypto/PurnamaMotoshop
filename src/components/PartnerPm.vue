<template>
      <div class="partner-logo" >
        <div class="container" >
          <carousel class="logo-carousel" :loop="true" :items="5" :dots="false" :naf="false" :autoplay="true">
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="img/logo-carousel/ak.png" alt=""  />
                    </div>
                </div>
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="img/logo-carousel/pertamina.png" alt="" />
                    </div>
                </div>
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="img/logo-carousel/logobumn.png" alt="" />
                    </div>
                </div>
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="img/logo-carousel/pt.png" alt="" />
                    </div>
                </div>
                <div class="logo-item">
                    <div class="tablecell-inner">
                        <img src="img/logo-carousel/ktc.png" alt="" />
                    </div>
                </div>
          </carousel>
        </div>
    </div>
</template>

<script>
import carousel from 'vue-owl-carousel';
export default {
    name:"PartnerPm",
    components:{
       carousel
   }
}
</script>