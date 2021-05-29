<template>
  <div class="home">
    <!-- Header Section Begin -->
   <HeaderPm/>
   <Hero/>
   <Best/>
   <GalleryPm/>
   <PartnerPm/>
    <FooterPm/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import HeaderPm from "@/components/HeaderPm.vue";
import Hero from "@/components/Hero.vue";
import Best from "@/components/Best.vue";
import GalleryPm from "@/components/GalleryPm.vue";
import PartnerPm from "@/components/PartnerPm.vue";
import FooterPm from "@/components/FooterPm.vue";
export default {
  name: "Home",
  components: {
    HeaderPm,
    Hero,
    Best,
    GalleryPm,
    PartnerPm,
    FooterPm
  },
};
</script>
