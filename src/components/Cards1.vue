<template>
  <div>
    <h1 class="fw-bold display-6 mb-5">Что делает 1С&#8209;программист?</h1>
    <swiper
      :slides-per-view="1"
      :space-between="60"
      loop
      :navigation="true"
      :modules="[ Autoplay, Navigation]"
      :autoplay="{
          delay: 3000,
          disableOnInteraction: false
        }"
      :speed="1000"
      :effect="slide"
      :breakpoints="swipbreakp"
    >
      <swiper-slide class="hhh">
        <div class = "bg-primary bg-opacity-25 rounded-4 p-4 p-lg-5 card1">
          <div class="row">
            <div class="col-4 col-sm-2 col-xl-2 pe-4 pe-sm-2 pe-xxl-4 mb-4 mb-xl-5">
              <img class="img-fluid pe-xxl-2" src="../assets/icon1.png" alt="">
            </div>
            <div class="col-sm-10 col-xl-10 mb-4 mb-xl-5 pe-0">
              <h4 class="fw-bold">Поддерживает систему управления на предприятии</h4>
            </div>
          </div>
          <div>
            <h4 class="mb-0">Моделирует и настраивает в 1С учет показателей компании, что помогает бизнесу их контролировать.</h4>
          </div>
        </div>
      </swiper-slide>
      <swiper-slide class="hhh">
        <div class = "bg-primary bg-opacity-25 rounded-4 p-4 p-lg-5 card1">
          <div class="row">
            <div class="col-4 col-sm-2 col-xl-2 pe-4 pe-sm-2 pe-xxl-4 mb-4 mb-xl-5">
              <img class="img-fluid pe-xxl-2" src="../assets/icon2.png" alt="">
            </div>
            <div class="col-sm-10 col-xl-10 mb-4 mb-xl-5">
              <h4 class="fw-bold col-xl-5">Программирует на&nbsp;языке&nbsp;1С</h4>
            </div>
          </div>
          <div>
            <h4 class="mb-0">Пишет и анализирует код, находит ошибки, исправляет и оптимизирует работу баз данных 1С. Ускоряет работу программы при больших данных.</h4>
          </div>
        </div>
      </swiper-slide>
      <swiper-slide class="hhh">
        <div class = "bg-primary bg-opacity-25 rounded-4 p-4 p-lg-5 card1">
          <div class="row">
            <div class="col-4 col-sm-2 col-xl-2 pe-4 pe-sm-2 pe-xxl-4 mb-4 mb-xl-5">
              <img class="img-fluid pe-xxl-2" src="../assets/icon3.png" alt="">
            </div>
            <div class="col-sm-10 col-xl-10 mb-4 mb-xl-5">
              <h4 class="fw-bold col-xxl-8">Обновляет существующие программы 1С</h4>
            </div>
          </div>
          <div>
            <h4 class="mb-0">Это позволяет бизнесу работать с учетом изменений в законодательстве, а также получать все новинки от 1С.</h4>
          </div>
        </div>
      </swiper-slide>
      <swiper-slide class="hhh">
        <div class = "bg-primary bg-opacity-25 rounded-4 p-4 p-lg-5 card1">
          <div class="row">
            <div class="col-4 col-sm-2 col-xl-2 pe-4 pe-sm-2 pe-xxl-4 mb-4 mb-xl-5">
              <img class="img-fluid pe-xxl-2" src="../assets/icon4.png" alt="">
            </div>
            <div class="col-sm-10 col-xl-10 col-xxl-8 mb-4 mb-xl-5">
              <h4 class="fw-bold">Разрабатывает и модифицирует функционал</h4>
            </div>
          </div>
          <div>
            <h4 class="mb-0">Для того, чтобы лучше отражать потребности бизнеса и оптимизировать систему учета на предприятии — делать ее более быстрой, удобной и функциональной.</h4>
          </div>
        </div>
      </swiper-slide>
    </swiper>
  </div>
</template>
<style>
.swiper{
  display: flex;
  flex-direction: column;
  align-items: center;
}
.swiper-button-next, .swiper-button-prev {
  position:relative;
  width: calc(var(--swiper-navigation-size)/ 44 * 27);
  height: 60px;
  width: 60px;
  margin-top: 0;
  z-index: 10;
  cursor: pointer;
  display: flex;
  align-items: center;
  justify-content: center;
  color: rgb(0, 0, 0);
  background-color: #65b1f0;
  border-radius: 6vh;
}
.swiper-button-next{
  left: 50px !important;
}
.swiper-button-prev{
  margin-top: 30px;
  margin-bottom: -60px;
  left: -50px !important;
}
.swiper-button-prev:after {
  content: url(../assets/Vector1.png);
}
.swiper-button-next:after {
  content: url(../assets/Vector2.png);
}
.card1{
  height: 330px;
}
@media (max-width: 410px) {
  .card1{
    height: 470px;
  }
}
@media (min-width:410px) and (max-width: 576px) {
  .card1{
    height: 400px;
  }
}
@media (min-width:576px) and (max-width: 992px) {
  .card1{
    height: 270px;
  }
}
</style>
<script>
import { Autoplay, Navigation } from 'swiper'
import { Swiper, SwiperSlide } from 'swiper/vue';
import 'swiper/css';
import 'swiper/css/autoplay';
import "swiper/css/navigation";

export default {
  name: 'HomeView',
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      Autoplay,
      Navigation,
      swipbreakp:{
        768:{
          slidesPerView: 1.4,
        },
        992:{
          slidesPerView: 1.6,
        },
        1200:{
          slidesPerView: 1.5,
        },
      }
    };
  },
}
</script>