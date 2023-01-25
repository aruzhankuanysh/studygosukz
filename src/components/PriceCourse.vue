<template>
  <section class="row justify-content-center position-relative">
    <div class="col-11 col-xl-10 row align-items-center">
      <div class="col-lg-6">
        <h1 class="fw-bold mb-4">
          Успейте занять место на&nbsp;курсе со&nbsp;скидкой
        </h1>
      </div>
      <div class="col-lg-6">
        <div class="row justify-content-center px-2">
          <div class="timer bg-primary rounded-4 p-2 row justify-content-center col-md-9 col-lg-12">
            <div class="timer__items d-flex justify-content-center bg-white rounded-4 col-sm-9 p-0">
              <div class="timer__item position-relative text-center h1 mx-3 timer__days">00</div>
              <div class="timer__item position-relative text-center h1 mx-3 timer__hours">00</div>
              <div class="timer__item position-relative text-center h1 mx-3 timer__minutes">00</div>
              <div class="timer__item position-relative text-center h1 mx-3 timer__seconds">00</div>
            </div>
            <div class="col-sm-3 text-center text-light mt-2">
              <h1 class="fw-bold m-0">50%</h1>
              <h5 class="fw-bold">скидка</h5>
            </div>
          </div>
        </div>
      </div>
      <h4 class="my-5 col-lg-8">Выберите подходящий вариант обучения и забронируйте место на курсе со скидкой</h4>
      <div class="col-6 d-none d-lg-block">
        <div class="card me-4">
          <div class="card-header pt-4 px-4">
            <h4 class="fw-bold">за 1 месяц</h4>
          </div>
          <div class="card-body px-0 mt-5">
            <div class="price col-11 py-4">
              <h2 class="text-center text-light fw-bold my-3 ps-4">100 000 ₸</h2>
            </div>
            <div class="text-center">
              <button class="btn btn-primary rounded-3 m-4 mt-5 px-5 py-2" type="button" data-bs-toggle="modal" data-bs-target="#exampleModal1">
                <h5 class="m-0 fw-bold">
                  Записаться на курс
                </h5>
              </button>
            </div>
          </div>
        </div>
      </div>
      <div class="col-6 d-none d-lg-block">
        <div class="card bg-primary ms-4 position-relative" style="overflow: hidden;">
          <div class="position-absolute bg-white px-5 top-0 end-0" id="sale">
            <h4 class="text-center mx-5">
              скидка
            </h4>
          </div>
          <div class="card-header pt-4 px-4">
            <h4 class="fw-bold text-light">при покупке 2 месяца </h4>
          </div>
          <div class="card-body px-0 mt-2 pt-3">
            <h4 class="text-decoration-line-through col-9 text-end mt-1">200 000 ₸</h4>
            <div class="price2 col-11 py-4">
              <h2 class="text-center fw-bold my-3 ps-4">150 000 ₸</h2>
            </div>
            <div class="text-center">
              <button class="btn btn-light rounded-3 m-4 mt-5 px-5 py-2" type="button" data-bs-toggle="modal" data-bs-target="#exampleModal1">
                <h5 class="m-0 fw-bold">
                  Записаться на курс
                </h5>
              </button>
            </div>
          </div>
        </div>
      </div>

      <div class="d-lg-none row justify-content-center px-4">
        <div class="card bg-primary position-relative col-sm-10 col-md-8 p-0" style="overflow: hidden;">
          <div class="card-header pt-4 px-0">
            <ul class="nav nav-tabs px-4" id="myTab" role="tablist">
              <li class="nav-item" role="presentation">
                <button class="nav-link active fw-bold" id="home-tab" data-bs-toggle="tab" data-bs-target="#home-tab-pane" type="button" role="tab" aria-controls="home-tab-pane" aria-selected="true">
                  2 месяца
                </button>
              </li>
              <li class="nav-item" role="presentation">
                <button class="nav-link fw-bold" id="profile-tab" data-bs-toggle="tab" data-bs-target="#profile-tab-pane" type="button" role="tab" aria-controls="profile-tab-pane" aria-selected="false">
                  1 месяц
                </button>
              </li>
            </ul>
            <div class="tab-content" id="myTabContent">
              <div class="tab-pane fade show active" id="home-tab-pane" role="tabpanel" aria-labelledby="home-tab" tabindex="0">
                <div class="position-absolute bg-white px-5 top-0 end-0" style="transform: rotate(41.45deg);top: 20px !important;; right:-95px!important;">
                  <h4 class="text-center mx-5">
                    скидка
                  </h4>
                </div>
                <div class="card-body px-0 mt-2 pt-3">
                  <h4 class="text-decoration-line-through col-9 text-end text-light mt-1">200 000 ₸</h4>
                  <div class="price2 py-4">
                    <h1 class="text-center fw-bold my-sm-3 ps-4">150 000 ₸</h1>
                  </div>
                  <div class="text-center">
                    <button class="btn btn-light rounded-3 m-4 mt-5 px-5 py-2" type="button" data-bs-toggle="modal" data-bs-target="#exampleModal1">
                      <h5 class="m-0 fw-bold">
                        Записаться на курс
                      </h5>
                    </button>
                  </div>
                </div>
              </div>
              <div class="tab-pane fade" id="profile-tab-pane" role="tabpanel" aria-labelledby="profile-tab" tabindex="0">
                <div class="card-body px-0 mt-5 pt-3">
                  <div class="price2 py-4">
                    <h1 class="text-center fw-bold my-sm-3 ps-4">100 000 ₸</h1>
                  </div>
                  <div class="text-center">
                    <button class="btn btn-light rounded-3 m-4 mt-5 px-5 py-2" type="button" data-bs-toggle="modal" data-bs-target="#exampleModal1">
                      <h5 class="m-0 fw-bold">
                        Записаться на курс
                      </h5>
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="py-5" id="reviews"></div>
      <div>
        <h1 class="fw-bold mb-5">
          Отзывы наших студентов
        </h1>
      </div>
      <div>
        <swiper
          :slides-per-view="1"
          :space-between="60"
          loop
          :modules="[Autoplay]"
          :autoplay="{
              delay: 3000,
              disableOnInteraction: false
            }"
          :centeredSlides="true"
          :speed="1000"
          :effect="slide"
          :breakpoints="swipbreakp"
        >
          <swiper-slide>
            <div class="card rounded-4" style="width: 100%; display: flex; align-items: center;" >
              <iframe width="347" height="618" src="https://www.youtube.com/embed/6H6QTPHnYQk" title="Отзыв о курсе Gosu Study" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
            <h2 class="text-center mt-4">Нур Арманулы</h2>
          </swiper-slide>
          <swiper-slide>
            <div class="card rounded-4" style="width: 100%; display: flex; align-items: center;">
              <iframe width="347" height="618" src="https://www.youtube.com/embed/JHbEgoZRmbg" title="Отзыв о курсе по 1с Gosu Study" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
            <h2 class="text-center mt-4">Кирилл Мухачев</h2>
          </swiper-slide>
          <swiper-slide>
            <div class="card rounded-4" style="width: 100%; display: flex; align-items: center;">
              <iframe class="rounded-4" width="347" height="618" src="https://www.youtube.com/embed/SPZ44Zen17Y" title="Отзыв о курсе Gosu Study 3" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
            </div>
            <h2 class="text-center mt-4">Владислав Столяров</h2>
          </swiper-slide>
        </swiper>
      </div>
      <div class="my-5"></div>
      <div>
        <h1 class="fw-bold mb-4">
          Сертификат о&nbsp;прохождении курса
        </h1>
      </div>
      <div class="text-center p-0 mb-5">
        <img class="col-xl-10 img-fluid" src="../assets/image10.png" alt="">
      </div>
    </div>
  </section>
</template>
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
        576:{
          slidesPerView: 1.4,
          centeredSlides:true
        },
        768:{
          slidesPerView: 1.8,
          centeredSlides:false
        },
        992:{
          slidesPerView: 2.3
        },
        1200:{
          slidesPerView: 3,
          autoplay: false
        },
      }
    };
  },
  mounted(){
    document.addEventListener('DOMContentLoaded', function() {
      // конечная дата, например 1 июля 2021
      const deadline = new Date(2023, 1, 1);
      // id таймера
      let timerId = null;
      // склонение числительных
      function declensionNum(num, words) {
        return words[(num % 100 > 4 && num % 100 < 20) ? 2 : [2, 0, 1, 1, 1, 2][(num % 10 < 5) ? num % 10 : 5]];
      }
      // вычисляем разницу дат и устанавливаем оставшееся времени в качестве содержимого элементов
      function countdownTimer() {
        const diff = deadline - new Date();
        if (diff <= 0) {
          clearInterval(timerId);
        }
        const days = diff > 0 ? Math.floor(diff / 1000 / 60 / 60 / 24) : 0;
        const hours = diff > 0 ? Math.floor(diff / 1000 / 60 / 60) % 24 : 0;
        const minutes = diff > 0 ? Math.floor(diff / 1000 / 60) % 60 : 0;
        const seconds = diff > 0 ? Math.floor(diff / 1000) % 60 : 0;
        $days.textContent = days < 10 ? '0' + days : days;
        $hours.textContent = hours < 10 ? '0' + hours : hours;
        $minutes.textContent = minutes < 10 ? '0' + minutes : minutes;
        $seconds.textContent = seconds < 10 ? '0' + seconds : seconds;
        $days.dataset.title = declensionNum(days, ['день', 'дня', 'дней']);
        $hours.dataset.title = declensionNum(hours, ['час', 'часа', 'часов']);
        $minutes.dataset.title = declensionNum(minutes, ['минута', 'минуты', 'минут']);
        $seconds.dataset.title = declensionNum(seconds, ['секунда', 'секунды', 'секунд']);
      }
      // получаем элементы, содержащие компоненты даты
      const $days = document.querySelector('.timer__days');
      const $hours = document.querySelector('.timer__hours');
      const $minutes = document.querySelector('.timer__minutes');
      const $seconds = document.querySelector('.timer__seconds');
      // вызываем функцию countdownTimer
      countdownTimer();
      // вызываем функцию countdownTimer каждую секунду
      timerId = setInterval(countdownTimer, 1000);
    });
  }
}
</script>
<style>
.price{
  background-image: url(../assets/elemPricePrimary.png);
  background-size: contain;
  background-repeat: no-repeat;
  background-position-x: center;
}
.price2{
  background-image: url(../assets/elemPriceWhite.png);
  background-size: contain;
  background-repeat: no-repeat;
  background-position-x: center;
}
.timer__item {
  padding-bottom: 15px;
}
.timer__item::before {
  content: attr(data-title);
  display: block;
  position: absolute;
  left: 50%;
  bottom: 0;
  transform: translateX(-50%);
  font-size: 14px;
}
.timer__item:not(:last-child)::after {
  content: ':';
  position: absolute;
  right: -15px;
}
#sale{
  transform: rotate(41.45deg);
  top: 35px !important;
  right:-70px!important;
}
</style>