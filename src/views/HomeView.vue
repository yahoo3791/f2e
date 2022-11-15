<template>
  <div class="container overflow-hidden">
    <div class="position-relative banner-height">
      <div class="row">
        <div class="col-12 col-md-6">
          <img src="@/assets/image/banner/Blue.png"
          class="w-100 d-none d-lg-block" alt=""
          data-aos="fade-right"
          data-aos-duration="1000"
          data-aos-delay="0"
          data-aos-anchor=".banner-height"
          data-aos-anchor-placement="top-top">
          <img src="@/assets/image/banner/mobile/Blue.png"
          class="d-block d-lg-none" style="object-fit:contain"
          data-aos="fade-right"
          data-aos-anchor=".navbar"
          data-aos-anchor-placement="top-top"
          data-aos-delay="0"
          data-aos-duration="100" alt="">
        </div>
        <div class="col-12 col-md-6 mt-5 mt-md-0 text-end">
          <img src="@/assets/image/banner/Yellow.png"
          class="w-100 d-none d-lg-block" alt=""
          data-aos="fade-left"
          data-aos-duration="1000"
          data-aos-delay="100"
          data-aos-anchor=".banner-height"
          data-aos-anchor-placement="top-top">
          <img src="@/assets/image/banner/mobile/Yellow.png"
          class="d-inline-block d-lg-none" style="object-fit:contain"
          data-aos="fade-left"
          data-aos-anchor=".navbar"
          data-aos-anchor-placement="top-top"
          data-aos-delay="100"
          data-aos-duration="200" alt="">
        </div>
        <div class="col-12 col-md-6 mt-5 mt-md-0 align-self-end">
          <img src="@/assets/image/banner/Red.png"
          class="w-100 d-none d-lg-block"
          data-aos="fade-right"
          data-aos-duration="1000"
          data-aos-delay="200"
          data-aos-anchor=".banner-height"
          data-aos-anchor-placement="top-top"
          alt="">
          <img src="@/assets/image/banner/mobile/Red.png"
          class="d-block d-lg-none banner-mobile-red" style="object-fit:contain"
          data-aos="fade-right"
          data-aos-anchor=".navbar"
          data-aos-anchor-placement="top-top"
          data-aos-delay="200"
          data-aos-duration="200"
          alt="">
        </div>
        <div class="col-12 col-md-6 mt-5 mt-md-0 text-end">
          <img src="@/assets/image/banner/Green.png"
          class="w-100 d-none d-lg-block"
          data-aos="fade-left"
          data-aos-duration="1000"
          data-aos-delay="300"
          data-aos-anchor=".banner-height"
          data-aos-anchor-placement="top-top" alt="">
          <img src="@/assets/image/banner/mobile/Green.png"
          class="d-inline-block d-lg-none" style="object-fit:contain"
          data-aos="fade-left"
          data-aos-duration="200"
          data-aos-anchor=".navbar"
          data-aos-anchor-placement="top-top"
          data-aos-delay="300" alt="">
        </div>
        <div class="Logo-center mt-5 mt-md-0 d-none d-md-block"
        data-aos="fade-down"
        data-aos-duration="1000"
        data-aos-delay="400"
        data-aos-anchor=".banner-height"
        data-aos-anchor-placement="top-top"
        ></div>
        <div class="Logo-center mt-5 mt-md-0 d-block d-md-none"
        data-aos="fade-down"
        data-aos-duration="200"
        data-aos-delay="100"
        data-aos-anchor=".banner-mobile-red"
        data-aos-anchor-placement="top-top"></div>
        <div class="position-absolute text-center start-50 translate-middle-x"
        :class="{'d-none': scrollClose}"
        style="top:50%;">
          <img src="@/assets/image/arrow-down-short.svg" class="scroll" alt="">
        </div>
      </div>
    </div>
  </div>
  <div class="container overflow-hidden">
    <h2 class="title-parimary aos-title">你是否也有以下困擾？</h2>
    <div class="row title-parimary aos">
      <div class="col-10 col-md-6 offset-2 offset-md-1">
          <img class="aosImg01 w-100"
          src="../assets/image/content/content01.png"
          data-aos="fade"
          data-aos-duration="1000"
          data-aos-delay="50">
      </div>
      <div class="col-10 col-md-5 offset-md-6 mt-5 mt-md-0">
          <img class="aosImg02 w-100"
          src="../assets/image/content/content02.png"
          data-aos="fade"
          data-aos-duration="1000"
          data-aos-delay="100" alt="">
      </div>
      <div class="col-10 col-md-6 offset-2 offset-md-1 mt-5 mt-md-0">
          <img class="aosImg03 w-100"
          src="../assets/image/content/content03.png"
          data-aos="fade"
          data-aos-duration="1000"
          data-aos-delay="150" alt="">
      </div>
    </div>
  </div>
  <div class="vector-bg"
    style="margin-top: -100px;"></div>
  <div class="container-fulid overflow-hidden"
    style="padding: 100px 0">
    <div class="position-relative">
      <div class="slogan d-flex">
        <div class="front">
          <img src="@/assets/image/slogan/Red.png" class="w-100"
          data-aos="fade-right"
          data-aos-duration="500"
          data-aos-easing="ease-in-out-back"
          alt="">
        </div>
        <div class="ui-designr">
          <img src="@/assets/image/slogan/Yellow.png" class="w-100"
          data-aos="fade-left"
          data-aos-duration="500"
          data-aos-delay="150"
          data-aos-easing="ease-in-out-back"
          alt="">
        </div>
      </div>
      <div class="position-absolute start-50 top-50 translate-middle"
      data-aos="fade">
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
    <div class="row aos02">
      <div class="col-8 col-md-6 align-self-center week1 week"
      style="z-index: 2">
        <img src="../assets/image/level/Week1.png"
        class="w-100 d-none d-lg-inline-block" alt="">
        <img src="../assets/image/level/Week1-mobile.png"
        class="d-inline-block d-md-none w-100" alt="">
      </div>
      <div class="col-6 offset-6 col-md-4 offset-md-2 my-md-5 py-md-5 fly">
        <img class="aosImg01 w-100" src="@/assets/image/level/week02.png" alt="">
      </div>
      <div class="col-6 col-md-4 my-md-5 py-md-5 fly2">
        <img class="aosImg02 w-100" src="@/assets/image/level/week03.png" alt="">
      </div>
      <div class="col-8 col-md-6 offset-4 offset-md-2 week2"
      style="z-index: 2">
        <img src="../assets/image/level/Week2.png"
        class="w-100 d-none d-lg-inline-block" alt="">
        <img src="../assets/image/level/Week2-mobile.png"
        class="d-inline-block d-md-none w-100" alt="">
      </div>
      <div class="col-8 col-md-6 week3"
      style="z-index: 2">
        <img src="../assets/image/level/Week3.png"
        class="w-100 d-none d-lg-inline-block" alt="">
        <img src="../assets/image/level/Week3-mobile.png"
        class="d-inline-block d-md-none w-100" alt="">
      </div>
      <div class="col-6 offset-6 col-md-4 offset-md-2 my-md-5 py-md-5 fly3">
        <img class="aosImg03 w-100" src="@/assets/image/level/scrum.png" alt="">
      </div>
    </div>
  </div>
  <div class="vector-bg"
    style="margin-top: -110px">
  </div>
  <div class="container process">
    <div class="row">
      <div class="col-12 col-md-4">
        <div class="mx-auto text-center" data-aos="fade">
          <div class="title title-parimary">報名時間</div>
          <p class="title-second">10/13~10/30<br>
          截止前可修改報名組別</p>
        </div>
      </div>
      <div class="col-12 col-md-4">
        <div class="mx-auto text-center" data-aos="fade">
          <div class="title title-parimary">開賽時間</div>
          <p class="title-second">10/31(一) UI、團體組開賽<br>
          11/7(一) 前端組開賽</p>
        </div>
      </div>
      <div class="col-12 col-md-4">
        <div class="mx-auto text-center" data-aos="fade">
          <div class="title title-parimary">登入作品</div>
          <p class="title-second">10/31~11/28<br>
          依賽程登錄作品</p>
        </div>
      </div>
      <div class="col d-none d-md-block"
        data-aos="fade"
        style="margin: 90px 0;">
        <div class="container process02">
          <div class="row">
            <div class="col-12 d-flex justify-content-around title-third">
              <div class="align-self-end">
                <img src="@/assets/image/process/processStart.png" alt="">
              </div>
              <div class="text-center">
                <div class="title">每週一</div>
                <p>獲得新主題</p>
              </div>
              <div class="text-center">
                <div class="title">隔週一</div>
                <p>UI組登錄作品，前端組領取設計稿</p>
              </div>
              <div class="text-center">
                <div class="title">再隔週一</div>
                <p>前端組登錄作品</p>
              </div>
            </div>
            <div class="col-12 text-center"
            data-aos="fade">
              <img src="../assets/image/process/processVector.png" class="w-100" alt="">
            </div>
          </div>
        </div>
      </div>
      <div class="col-7 col-md-12 mx-auto text-center paragraph my-5"
      data-aos="fade">
        <p>
          活動採用 UI、前端接力合作形式，前端工程師可採用 UI 設計師的設計稿，一同產出完整作品。
        </p>
      </div>
      <div class="col-6 mx-auto d-block d-md-none mb-5 mb-md-0"
        data-aos="fade">
        <img src="@/assets/image/process/process02.png" class="w-100" alt="">
      </div>
    </div>
  </div>
  <div class="container-fulid mt-5">
    <div class="slogan03 position-relative">
      <p class="paragraph">區區修煉已經無法滿足了嗎？</p>
      <div class="title-parimary">還有比賽等著你！</div>
    </div>
  </div>
  <div class="container d-md-flex" style="padding-top: 170px">
      <div class="process-left" data-aos="fade">
        <img src="@/assets/image/process/process-green.png" class="w-100" alt="">
      </div>
      <div class="process-right" data-aos="fade">
        <img src="@/assets/image/process/process-blue.png" class="w-100" alt="">
      </div>
  </div>
  <div class="vector-bg"
    style="margin-top: -150px">
  </div>
  <div class="text-center"
    data-aos="fade">
    <a href="https://2022.thef2e.com/signup"
    class="actionBtn href-none"
    style="margin-bottom: 175px">立即報名</a>
  </div>
  <div class="container">
    <div class="row justify-content-center">
      <div class="col-12 text-center">
        <h3 class="title-parimary pb-5" style="line-height: 55px">
          鑽石級贊助商<br>
          SPONSORS
        </h3>
      </div>
      <div class="col-12 col-md-3 text-center"
      data-aos="fade">
        <a href="https://blockstudio.tw/"
        class="d-inline-block sponsorBtn">
          <img src="@/assets/image/sponsorBlockStudio.png" alt="blockstudio">
        </a>
      </div>
      <div class="col-12 col-md-3 text-center mt-5 mt-md-0"
      data-aos="fade">
        <a href="https://titansoft.com/tw"
        class="d-inline-block sponsorBtn">
          <img src="@/assets/image/sponsor鈦坦.png" alt="鈦坦">
        </a>
      </div>
      <div class="col-12 col-md-3 text-center mt-5 mt-md-0"
      data-aos="fade">
        <a href="https://www.kdanmobile.com/zh-tw"
        class="d-inline-block sponsorBtn">
          <img src="@/assets/image/sponsorKDAN.png" alt="KDAN">
        </a>
      </div>
    </div>
  </div>
  <!-- arrowup -->
  <div class="TopBtn d-none d-md-block" :class="{'TopBtn1': TopBtn}"
    @click="goToTop"
    @keypress="goToTop"></div>
</template>

<script>
import AOS from 'aos';
import 'aos/dist/aos.css';
import gsap from 'gsap';
import ScrollTrigger from 'gsap/ScrollTrigger';

gsap.registerPlugin(ScrollTrigger);

export default {
  data() {
    return {
      TopBtn: true,
      scrollClose: false,
    };
  },
  methods: {
    goToTop() {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    },
    handleScroll() {
      const pageWidth = document.documentElement.scrollWidth;
      const pageHeight = window.scrollY;
      if (pageWidth >= 1024 && pageHeight >= 3000) {
        this.TopBtn = true;
      } else {
        this.TopBtn = false;
      }
      if (pageHeight >= 1) {
        this.scrollClose = true;
      } else {
        this.scrollClose = false;
      }
    },
  },
  created() {
    window.addEventListener('scroll', this.handleScroll);
  },
  mounted() {
    AOS.init();
    const pageWidth = document.documentElement.scrollWidth;
    if (pageWidth >= 1024) {
      gsap.to('.week', {
        scrollTrigger: {
          trigger: '.week1',
          start: 'top 10%',
          end: 'bottom 0%',
          pin: true,
        },
      });
      gsap.to('.week', {
        scrollTrigger: {
          trigger: '.week2',
          start: 'top 30%',
          end: 'bottom 50%',
          pin: true,
        },
      });
      gsap.to('.week', {
        scrollTrigger: {
          trigger: '.week3',
          start: 'top 60%',
          end: 'bottom 80%',
          pin: true,
        },
      });
    } else if (pageWidth <= 1024) {
      gsap.to('.aos02', {
        scrollTrigger: {
          trigger: '.week1',
          start: 'top 20%',
          end: 'bottom 20%',
          pin: true,
        },
      });
      gsap.to('.aos02', {
        scrollTrigger: {
          trigger: '.week2',
          start: 'top 40%',
          end: 'bottom 50%',
          pin: true,
        },
      });
      gsap.to('.aos02', {
        scrollTrigger: {
          trigger: '.week3',
          start: 'top 60%',
          end: 'bottom 60%',
          pin: true,
        },
      });
    }
  },
};
</script>
