<template>
  <div class="main">
    <section>
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
    <section class="container py-100 mb-100 mt-50">
      <div style="position: relative">
        <div class="d-flex justify-content-center align-items-center">
          <div
            class="text-center text-cormorant text-italic fs-130"
            style="position:absolute;  margin-top: 220px; line-height: 100px; z-index:-1;  opacity: 0.03"
          >
            Мы любим и гордимся <br />
            нашим Рыбинским
            <br />
            театром кукол!
          </div>
        </div>
        <div class=" d-flex justify-content-center align-items-center">
          <div class="text-center">
            <div class="text-cormorant mb-50 fs-60">
              Добро пожаловать в <br />
              Рыбинский Театр Кукол!
            </div>
            <div class="mt-50">
              Рыбинский театр кукол — это настоящий дворец,<br />
              где живут куклы из любимых сказок. Наш театр кукол известен,
              <br />как один из первых театров кукол России.
            </div>
            <div
              class="text-cormorant text-italic mt-50 text-gold fs-28"
              style="line-height: 0px;"
            >
              1932
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="py-50" style="background-color: black">
      <div class="container text-white">
        <div class="d-flex justify-content-center text-cormorant fs-28 mb-40 ">
          <div class="pb-20">
            <div>Афиша</div>
            <div class="d-flex justify-content-center mt-10">
              <img src="/images/decor.png" alt="" />
            </div>
          </div>
        </div>
        <div class="news-card cursor">
          <div class="row d-flex justify-content-center align-items-center">
            <div class="col-lg my-10">
              <img
                src="/images/news-1.jpg"
                width="100%"
                style="object-fit:cover"
              />
            </div>
            <div
              class="col-lg my-10 d-flex justify-content-center align-items-center"
            >
              <div
                class="text-cormorant text-italic fs-130 mr-30"
                style="color: #dedede;"
              >
                06
              </div>
              <div>
                <div class="text-cormorant fs-28">Мая</div>
                <div>
                  суббота
                </div>
              </div>
            </div>
            <div class="col-lg-4 my-10 d-flex justify-content-center">
              <div class="text-center">
                <div class="text-cormorant fs-28">
                  «ТЕРЕМ-ТЕРЕМОК» 0+
                </div>
                <div>
                  Май 06, 2021
                </div>
                <div>
                  Город Рыбинск
                </div>
              </div>
            </div>
            <div class="col-lg my-10 d-flex justify-content-center">
              <button class="btn-fill-golden">подробнее</button>
            </div>
          </div>
        </div>
        <div class="news-card">
          <div class="row d-flex justify-content-center align-items-center">
            <div class="col-lg my-10">
              <img
                src="/images/news-2.jpg"
                width="100%"
                style="object-fit:cover"
              />
            </div>
            <div
              class="col-lg my-10 d-flex justify-content-center align-items-center"
            >
              <div
                class="text-cormorant text-italic fs-130 mr-30"
                style="color: #dedede;"
              >
                14
              </div>
              <div>
                <div class="text-cormorant fs-28">Апреля</div>
                <div>
                  воскресенье
                </div>
              </div>
            </div>
            <div class="col-lg-4 my-10 d-flex justify-content-center">
              <div class="text-center">
                <div class="text-cormorant fs-28">
                  «В стране дорожных знаков»
                </div>
                <div>
                  Апрель 14, 2021
                </div>
                <div>
                  Город Рыбинск
                </div>
              </div>
            </div>
            <div class="col-lg my-10 d-flex justify-content-center">
              <button class="btn-fill-golden">подробнее</button>
            </div>
          </div>
        </div>
        <div class="news-card">
          <div class="row d-flex justify-content-center align-items-center">
            <div class="col-lg my-10">
              <img
                src="/images/news-3.jpg"
                width="100%"
                style="object-fit:cover"
              />
            </div>
            <div
              class="col-lg my-10 d-flex justify-content-center align-items-center"
            >
              <div
                class="text-cormorant text-italic fs-130 mr-30"
                style="color: #dedede;"
              >
                02
              </div>
              <div>
                <div class="text-cormorant fs-28">Апреля</div>
                <div>
                  суббота
                </div>
              </div>
            </div>
            <div class="col-lg-4 my-10 d-flex justify-content-center">
              <div class="text-center">
                <div class="text-cormorant fs-28">
                  «Приключения Буратино»
                </div>
                <div>
                  Апрель 02, 2021
                </div>
                <div>
                  Город Рыбинск
                </div>
              </div>
            </div>
            <div class="col-lg my-10 d-flex justify-content-center">
              <button class="btn-fill-golden">подробнее</button>
            </div>
          </div>
        </div>
        <div class="text-center text-cormorant text-italic my-50">
          <a href="" class="text-gold">Больше афиш..</a>
        </div>
      </div>
    </section>

    <section class="container py-50">
      <div class="d-flex justify-content-center text-cormorant fs-28 mb-40 ">
        <div class="pb-20">
          <div>Новости</div>
          <div class="d-flex justify-content-center mt-10">
            <img src="/images/decor.png" alt="" />
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-6 my-30">
          <div class="row">
            <div class="col">
              <img
                src="/images/journal-1.jpg"
                width="100%"
                class="journal-img"
              />
            </div>
            <div class="col">
              <div
                class="p-10 "
                style="margin-top: -10px; margin-left: -70px; background-color: white"
              >
                <div class="d-flex justify-content-between">
                  <div>
                    <div class="fs-14">
                      20/05/2021
                    </div>
                  </div>
                  <div class="fs-14 text-gold">
                    Спектакль
                  </div>
                </div>
                <div class="text-cormorant text-italic fs-22">
                  Серебрянное копытце
                </div>
              </div>
              <div class="mt-20 fs-14">
                В Рыбинском театре кукол идет подготовка к новому спектаклю
                "Серебряное копытце", премьера которого состоится 22 и 23 мая.
                «Серебряное копытце» — сказка Павла Петровича Бажова, любимая
                ...
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-6 my-30">
          <div class="row">
            <div class="col">
              <img
                src="/images/journal-2.jpg"
                width="100%"
                class="journal-img"
              />
            </div>
            <div class="col">
              <div
                class="p-10 "
                style="margin-top: -10px; margin-left: -70px; background-color: white"
              >
                <div class="d-flex justify-content-between">
                  <div>
                    <div class="fs-14">
                      20/05/2021
                    </div>
                  </div>
                  <div class="fs-14 text-gold">
                    Спектакль
                  </div>
                </div>
                <div class="text-cormorant text-italic fs-22">
                  Серебрянное копытце
                </div>
              </div>
              <div class="mt-20 fs-14">
                В Рыбинском театре кукол идет подготовка к новому спектаклю
                "Серебряное копытце", премьера которого состоится 22 и 23 мая.
                «Серебряное копытце» — сказка Павла Петровича Бажова, любимая
                ...
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-6 my-30">
          <div class="row">
            <div class="col">
              <img
                src="/images/journal-3.jpg"
                width="100%"
                class="journal-img"
              />
            </div>
            <div class="col">
              <div
                class="p-10 "
                style="margin-top: -10px; margin-left: -70px; background-color: white"
              >
                <div class="d-flex justify-content-between">
                  <div>
                    <div class="fs-14">
                      20/05/2021
                    </div>
                  </div>
                  <div class="fs-14 text-gold">
                    Спектакль
                  </div>
                </div>
                <div class="text-cormorant text-italic fs-22">
                  Серебрянное копытце
                </div>
              </div>
              <div class="mt-20 fs-14">
                В Рыбинском театре кукол идет подготовка к новому спектаклю
                "Серебряное копытце", премьера которого состоится 22 и 23 мая.
                «Серебряное копытце» — сказка Павла Петровича Бажова, любимая
                ...
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-6 my-30">
          <div class="row">
            <div class="col">
              <img
                src="/images/journal-4.jpg"
                width="100%"
                class="journal-img"
              />
            </div>
            <div class="col">
              <div
                class="p-10 "
                style="margin-top: -10px; margin-left: -70px; background-color: white"
              >
                <div class="d-flex justify-content-between">
                  <div>
                    <div class="fs-14">
                      20/05/2021
                    </div>
                  </div>
                  <div class="fs-14 text-gold">
                    Спектакль
                  </div>
                </div>
                <div class="text-cormorant text-italic fs-22">
                  Серебрянное копытце
                </div>
              </div>
              <div class="mt-20 fs-14">
                В Рыбинском театре кукол идет подготовка к новому спектаклю
                "Серебряное копытце", премьера которого состоится 22 и 23 мая.
                «Серебряное копытце» — сказка Павла Петровича Бажова, любимая
                ...
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="text-center text-cormorant text-italic my-50">
        <a href="" class="text-gold">Больше новостей..</a>
      </div>
    </section>

    <section
      class="fs-28 text-center  text-cormorant py-50"
      style="background-color: #f7f7f7;"
    >
      <div class="container">
        Подпишитесь на наш
        <a href="" class="text-gold" style="text-decoration: underline">
          instagram
        </a>
      </div>
    </section>

    <section
      class="py-100"
      style="background-color: black; border-bottom: 1px solid #242424"
    >
      <div class="container">
        <div class="row">
          <div class="col-lg">
            <img
              src="/images/footer-map.jpg"
              width="100%"
              style="object-fit: cover"
            />
          </div>
          <div class="col-lg">
            <div class="text-cormorant text-italic text-white fs-22 mb-30">
              Информация
            </div>
            <div class="my-20 fs-14" style="color: rgba(255,255,255,0.4)">
              <i class="bi bi-geo-alt text-gold"></i>
              г. Рыбинск, ул. Вокзальная, 14
            </div>
            <div class="my-20 fs-14" style="color: rgba(255,255,255,0.4)">
              <i class="bi bi-envelope text-gold"></i>
              teatr-kukol-rybinsk@yandex.ru
            </div>
            <div class="my-20 fs-14" style="color: rgba(255,255,255,0.4)">
              <i class="bi bi-telephone text-gold"></i>
              <a href="tel:4855217027" style="color: rgba(255,255,255,0.4)">
                (4855) 21 - 70 - 27
              </a>
            </div>
          </div>
          <div class="col-lg">
            <div class="text-cormorant text-italic text-white fs-22 mb-30">
              Режим работы кассы:
            </div>
            <div class="my-20 fs-14" style="color: rgba(255,255,255,0.4)">
              понедельник — выходной,
            </div>
            <div class="my-20 fs-14" style="color: rgba(255,255,255,0.4)">
              вторник — пятница 11.00 — 18.00 перерыв 13.00-14.00,
            </div>
            <div class="my-20 fs-14" style="color: rgba(255,255,255,0.4)">
              суббота, воскресенье 9.00-15.00,
            </div>
          </div>
          <div class="col-lg"></div>
        </div>
      </div>
    </section>
    <section class="py-100" style="background-color: black;">
      <div class="container d-flex justify-content-center">
        <div>
          <div class="d-flex justify-content-center">
            <i class="bi bi-instagram text-gold px-10"></i>
            <i class="bi bi-facebook text-gold px-10"></i>
            <i class="bi bi-twitter text-gold px-10"></i>
            <i class="bi bi-youtube text-gold px-10"></i>
          </div>
          <div class=" text-center text-cormorant text-white mt-20 fs-28">
            Рыбинский Театр Кукол
          </div>
          <div class="fs-12 text-center mt-20">
            © 2021. Рыбинский театр кукол / Разработано командой
            <a
              href="https://mirllex.space"
              style="color: #212529; text-decoration: underline"
            >
              mirllex
            </a>
          </div>
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
  .news-card {
    padding: 50px 0px;
    border-top: 1px solid #ccc;
  }
  .journal-img {
    object-fit: cover;
    width: 300px;
    height: 300px;
  }
  @media (max-width: 1200px) {
    .journal-img {
      object-fit: cover;
      width: 150px;
      height: 150px;
    }
  }
}
</style>
