<template>
  <div class="home">
      <HeaderQiow />
      <HeroQiow />
      <ItemsQiow />
      <!-- <GalleryQiow />
      <PartnerQiow /> -->
      <FooterQiow />
  </div>
  
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderQiow from "@/components/HeaderQiow.vue";
import HeroQiow from "@/components/HeroQiow.vue";
import ItemsQiow from "@/components/ItemsQiow.vue";
// import GalleryQiow from "@/components/GalleryQiow.vue";
// import PartnerQiow from "@/components/PartnerQiow.vue";
import FooterQiow from "@/components/FooterQiow.vue";

export default {
  name: 'home',
  components: {
    HeaderQiow,
    HeroQiow,
    ItemsQiow,
   // GalleryQiow,
   // PartnerQiow,
    FooterQiow,
  }
}
</script>
