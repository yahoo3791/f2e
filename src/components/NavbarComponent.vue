<template>
  <!-- desktop -->
  <div class="container justify-content-between
  align-items-center navbar d-none d-lg-flex aa">
    <div class="logo" style="cursor: pointer;">
      <img src="@/assets/image/LOGO.png" alt="Logo image">
    </div>
    <div class="d-flex title-third">
        <ul class="nav">
          <li><a href="https://2022.thef2e.com/news" class="smallBtn href-none">關卡資訊</a></li>
          <li><a href="https://2022.thef2e.com/works" class="smallBtn href-none">作品列表</a></li>
          <li><a href="https://hackmd.io/ofJD4K7iSI65V19zxC7d0w" class="smallBtn href-none">攻略資源</a></li>
          <li><a href="https://2022.thef2e.com/jobs" class="smallBtn href-none">求職專區</a></li>
          <li><a href="https://2022.thef2e.com/login" class="smallBtn href-none">登入</a></li>
        </ul>
      <a href="https://2022.thef2e.com/signup" class="d-block href-none actionBtnNav"
      style="margin-right:8px">立即報名</a>
    </div>
  </div>
  <!-- mobile -->
  <div class="container-fulid d-block d-lg-none border navbar">
    <div class="position-relative d-flex justify-content-between
      align-items-center w-100">
      <div class="mobileBtn"
        @click="mobBoolean = !mobBoolean"
        @keypress="mobBoolean = !mobBoolean"
        style="z-index: 2;"></div>
      <a href="https://2022.thef2e.com/signup"
        class="d-block href-none actionBtnNav"
        style="z-index: 2;">立即報名</a>
      <div class="position-absolute start-0 w-100"
        style="top: 50px;">
        <div class="mobileNav bg-white"
          :class="{ 'openMobileNav': mobBoolean }">
          <ul>
            <li><a href="https://2022.thef2e.com/news" class="d-block href-none">關卡資訊</a></li>
            <li><a href="https://2022.thef2e.com/works" class="d-block href-none">作品列表</a></li>
            <li><a href="https://hackmd.io/ofJD4K7iSI65V19zxC7d0w" class="d-block href-none">攻略資源</a></li>
            <li><a href="https://2022.thef2e.com/jobs" class="d-block href-none">求職專區</a></li>
            <li><a href="https://2022.thef2e.com/login" class="d-block href-none">登入</a></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      mobBoolean: false,
    };
  },
};
</script>
