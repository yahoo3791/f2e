<template>
  <Navbar />
  <router-view/>
  <!-- <div class="actionBtn">立即報名</div>
  <div class="sponsorBtn">
    <img src="@/assets/image/sponsorBlockStudio.png" alt="">
  </div>
  <div class="TopBtn"></div>
  <div class="smallBtn">關卡資訊</div>
  <div class="mobileBtn"></div>
  <div class="actionBtnNav">立即報名</div> -->
  <Footer />
</template>

<style lang="scss">
@import "@/assets/scss/all.scss";
</style>

<script>
import Navbar from '@/components/NavbarComponent.vue';
import Footer from '@/components/FooterComponent.vue';

export default {
  components: {
    Navbar, Footer,
  },
};
</script>
