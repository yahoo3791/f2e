<template>
  <div class="container p-0">
    <div class="position-relative border banner-height">
      <div class="blue border position-absolute"></div>
      <div class="yellow border position-absolute"></div>
      <div class="red border position-absolute"></div>
      <div class="green border position-absolute"></div>
      <div class="Logo-center position-absolute translate-middle top-50 start-50"></div>
    </div>
  </div>
  <div class="container">
    <h2 style="padding: 250px 0 70px 200px">你是否也有以下困擾？</h2>
    <div class="row">
      <div class="col-12 col-md-6 offset-md-1">
        <div class="position-relative border">
          <img src="../assets/image/content/content01.png" alt="">
          <div class="position-absolute border translate-middle"
          style="top: 80px;left: 45%">羨慕別人的酷酷網頁動畫</div>
        </div>
      </div>
      <div class="col-12 col-md-5 offset-md-6">
        <div class="position-relative border">
          <img src="../assets/image/content/content02.png" alt="">
          <div class="position-absolute start-50 border translate-middle"
          style="top: 80px">羨慕別人的酷酷網頁動畫</div>
        </div>
      </div>
      <div class="col-12 col-md-6 offset-md-1">
        <div class="position-relative border">
          <img src="../assets/image/content/content03.png" alt="">
          <div class="position-absolute border translate-middle"
          style="top: 80px;left: 45%">羨慕別人的酷酷網頁動畫</div>
        </div>
      </div>
    </div>
  </div>
  <div class="vector-bg"
    style="margin-top: -100px;"></div>
  <div class="container-fulid border"
    style="padding: 100px 0">
    <div class="position-relative">
      <div class="slogan">
        <div class="front position-absolute"></div>
        <div class="ui-designr position-absolute"></div>
      </div>
      <div class="position-absolute start-50 top-50 translate-middle">
        <div class="slogan-title"></div>
      </div>
    </div>
  </div>
  <div class="container-fulid">
    <div class="slogan02 position-relative">
      <div class="title-parimary">年度最強合作，三大主題來襲</div>
      <p class="paragraph">各路廠商強強聯手，共同設計出接地氣的網頁互動挑戰關卡</p>
    </div>
  </div>
  <div class="vector-bg"
    style="margin-top: -150px">
  </div>
  <div class="container">
    <div class="row">
      <div class="col-6 offset-6">
        <img src="@/assets/image/level/week02.png" alt="">
      </div>
      <div class="col-12">
        <img src="@/assets/image/level/week03.png" alt="">
      </div>
      <div class="col-6 offset-6">
        <img src="@/assets/image/level/scrum.png" alt="">
      </div>
    </div>
  </div>
  <div class="vector-bg"
    style="margin-top: -150px">
  </div>
  <div class="container"
    style="margin-top: -100px">
    <div class="row">
      <div class="col-12 col-md-4">
        <div class="mx-auto text-center">
          <div class="title">報名時間</div>
          <p>10/13~10/30<br>
          截止前可修改報名組別</p>
        </div>
      </div>
      <div class="col-12 col-md-4">
        <div class="mx-auto text-center">
          <div class="title">開賽時間</div>
          <p>10/31(一) UI、團體組開賽<br>
          11/7(一) 前端組開賽</p>
        </div>
      </div>
      <div class="col-12 col-md-4">
        <div class="mx-auto text-center">
          <div class="title">登入作品</div>
          <p>10/31~11/28<br>
          依賽程登錄作品</p>
        </div>
      </div>
      <div class="col d-none d-md-block"></div>
      <div class="col-12 text-center">
        <p>
          活動採用 UI、前端接力合作形式，前端工程師可採用 UI 設計師的設計稿，一同產出完整作品。
        </p>
      </div>
      <div class="col d-none d-md-none"></div>
    </div>
  </div>
  <div class="container-fulid">
    <div class="slogan03 position-relative">
      <p class="paragraph">區區修煉已經無法滿足了嗎？</p>
      <div class="title-parimary">還有比賽等著你！</div>
    </div>
  </div>
  <div class="vector-bg"
    style="margin-top: -150px">
  </div>
  <div class="text-center">
    <div class="actionBtn"
    style="margin-bottom: 175px">立即報名</div>
  </div>
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-12 text-center">
        <h3>
          鑽石級贊助商<br>
          SPONSORS
        </h3>
      </div>
      <div class="col-12 col-md-3 text-center">
        <div class="sponsorBtn">
          <img src="@/assets/image/sponsorBlockStudio.png" alt="">
        </div>
      </div>
      <div class="col-12 col-md-3 text-center">
        <div class="sponsorBtn">
          <img src="@/assets/image/sponsor鈦坦.png" alt="">
        </div>
      </div>
      <div class="col-12 col-md-3 text-center">
        <div class="sponsorBtn">
          <img src="@/assets/image/sponsorKDAN.png" alt="">
        </div>
      </div>
    </div>
  </div>
  <!-- arrowup -->
  <div class="TopBtn"
    @click="goToTop"
    @keypress="goToTop"></div>
</template>

<script>
export default {
  data() {
    return {};
  },
  methods: {
    goToTop() {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    },
  },
};
</script>
