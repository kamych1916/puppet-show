<template>
  <div>
    <section class="main">
      <div class="slider w-100">
        <hooper
          group="group1"
          :itemsToShow="1"
          :autoPlay="true"
          :playSpeed="5000"
          :transition="900"
          :wheelControl="false"
        >
          <slide>
            <img
              src="/images/slider-1.jpg"
              width="100%"
              height="100%"
              class="w-100 h-100"
              style="object-fit:cover"
            />
            <div class="backdrop w-100"></div>
            <div class="text ">
              <div class="title fs-130">
                Алмазные подвески
              </div>
              <div class="title text-center fs-22 mb-20">В. ЗВЕРОВЩИКОВ</div>
              <div class="text-center fs-14 mb-20">7 и 8 мая, воскресенье</div>
              <div class="w-100 d-flex justify-content-center">
                <button class="btn-fill-white m-10 fs-12">купить билет</button>
                <button class="btn-white m-10 fs-12">подробнее</button>
              </div>
            </div>
          </slide>
          <slide>
            <img
              src="/images/slider-2.jpg"
              width="100%"
              height="100%"
              class="w-100 h-100"
              style="object-fit:cover"
            />
            <div class="backdrop w-100"></div>
            <div class="text ">
              <div class="title fs-130">
                Танец дракона
              </div>
              <div class="title text-center fs-22 mb-20">П. Бажов</div>
              <div class="text-center fs-14 mb-20">
                15 и 16 мая, воскресенье
              </div>
              <div class="w-100 d-flex justify-content-center">
                <button class="btn-fill-white m-10 fs-12">купить билет</button>
                <button class="btn-white m-10 fs-12">подробнее</button>
              </div>
            </div>
          </slide>
          <hooper-navigation slot="hooper-addons"></hooper-navigation>
        </hooper>
      </div>
    </section>
    <section class="bg-black py-40 px-30 text-white ">
      <div class="container d-flex justify-content-between align-items-center">
        <div>
          <div class="text-cormorant fs-28">
            Купить билеты
            <!-- Get your tickets -->
          </div>
          <div class="text-grey fs-12">
            Выберите спектакль и день, в который вы хотите его посмотреть.
          </div>
        </div>
        <div>
          <button class="btn-fill-golden fs-14">купить билеты</button>
        </div>
      </div>
    </section>
    <section class="d-flex justify-content-center align-items-center p-100">
      <div style="position: relative">
        <!-- <div
          style="position:absolute; z-index:-1; top:-100px; left: -400px; opacity: 0.4"
        >
          <img
            src="/images/backdrop-text.png"
            width="150%"
            style="object-fit: cover"
          />
        </div> -->
        <div
          class="text-center text-cormorant mb-50"
          style="font-size: 60px; line-height: 60px; font-style: normal;"
        >
          Добро пожаловать в <br />
          Кукольный Театр Рыбинска!
        </div>
        <div class="text-center mt-50">
          Рыбинский театр кукол — это настоящий дворец,<br />
          где живут куклы из любимых сказок. Наш театр кукол известен, <br />как
          один из первых театров кукол России.
        </div>
      </div>
    </section>
    <section class="d-flex justify-content-center " style="height: 100vh; ">
      <div class="text-cormorant fs-28  ">
        <div>Афиша</div>
        <div class="d-flex justify-content-center mt-20">
          <img src="/images/decor.png" alt="" />
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import { Hooper, Slide, Navigation as HooperNavigation } from "hooper";
import "hooper/dist/hooper.css";
export default {
  components: {
    Hooper,
    Slide,
    HooperNavigation
  },
  data() {
    return {
      name: ""
    };
  }
};
</script>

<style lang="scss">
.main {
  position: relative;
  .slider {
    position: relative;
    height: 100vh;
    .backdrop {
      position: absolute;
      width: 100%;
      height: 100%;
      background: black;
      opacity: 0.5;
    }
    .text {
      position: absolute;
      color: white;
      text-shadow: 10px 2px 30px black;
      .title {
        font-family: Cormorant;
        font-style: italic;
        color: #fff;
        letter-spacing: 2px;
      }
    }
  }
}
</style>
