<template>
  <div class="container-fluid bg-dark text-light row justify-content-center">
    <section class="row justify-content-center position-relative p-0 pt-5">
      <img class="img-fluid col-5 position-absolute start-0 mt-5 pt-5 d-none d-lg-block" src="../assets/image2.png" alt="">

        <h1 class="fw-bold display-6 text-center mb-xl-5">5 причин стать программистом&nbsp;на&nbsp;1С</h1>
        <div class="col-lg-5">
        </div>
        <div class="col-lg-7 my-5 p-0">
          <div class="my-xl-5"></div>
          <div>
            <swiper
            :slides-per-view="1.1"
            :space-between="60"
            :centeredSlides="true"
            loop
            :autoHeight="false"
            :modules="[Autoplay]"
            :autoplay="{
                delay: 3000,
                disableOnInteraction: false
              }"
            :speed="1000"
            :effect="slide"
            :breakpoints="swipbreakpoints"
          >
            <swiper-slide>
              <div class = "bg-white bg-opacity-10 rounded-4 p-4 card2">
                <div class="p-2">
                  <div class="col-2 pb-2 pe-1">
                    <h3 class="bg-primary rounded-3 fw-bold text-center py-2">1</h3>
                  </div>
                  <h4 class="fw-bold my-4">У вас всегда будет работа</h4>
                  <h6 class="mb-0">
                    Программа 1с - автоматизирует деятельность компании, абсолютно любой, от магазина у дома до крупного производства. Если не замечали раньше, то обязательно обратите внимание, как в любом магазине, тц, на предприятиях, да везде на компьютерах открыта программа 1с, так как она очень популярна в автоматизации бизнеса.
                  </h6>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide>
              <div class = "bg-white bg-opacity-10 rounded-4 p-4 card2">
                <div class="p-2">
                  <div class="col-2 pb-2 pe-1">
                    <h3 class="bg-primary rounded-3 fw-bold text-center py-2">2</h3>
                  </div>
                  <h4 class="fw-bold my-4">Возможность работать удаленно и зарабатывать на фрилансе </h4>
                  <h6 class="mb-0">
                    Для 1С-разработки есть отдельные фриланс-биржи.
                  </h6>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide>
              <div class = "bg-white bg-opacity-10 rounded-4 p-4 card2">
                <div class="p-2">
                  <div class="col-2 pb-2 pe-1">
                    <h3 class="bg-primary rounded-3 fw-bold text-center py-2">3</h3>
                  </div>
                  <h4 class="fw-bold my-4">Высокий доход</h4>
                  <h6 class="mb-0">
                    Средняя зарплата 1с-программиста в Казахстане - 500&nbsp;000&nbsp;тг
                  </h6>
                  <a target="blank_" href="https://almaty.hh.kz/search/vacancy?area=160&search_field=name&search_field=company_name&search_field=description&salary=403200&only_with_salary=true&text=1%D1%81+%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%81%D1%82&from=suggest_post&ored_clusters=true&enable_snippets=true">
                    <button class="btn btn-outline-light px-4 py-2 mt-5">
                      Посмотреть актульные вакансии
                    </button> 
                  </a>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide>
              <div class = "bg-white bg-opacity-10 rounded-4 p-4 card2">
                <div class="p-2">
                  <div class="col-2 pb-2 pe-1">
                    <h3 class="bg-primary rounded-3 fw-bold text-center py-2">4</h3>
                  </div>
                  <h4 class="fw-bold my-4">Не нужно знать английский язык для работы и обучения</h4>
                  <h6 class="mb-0">
                    Весь код и документация 1С — на русском языке. Легко разобраться и писать код.
                  </h6>
                </div>
              </div>
            </swiper-slide>
            <swiper-slide>
              <div class = "bg-white bg-opacity-10 rounded-4 p-4 card2">
                <div class="p-2">
                  <div class="col-2 pb-2 pe-1">
                    <h3 class="bg-primary rounded-3 fw-bold text-center py-2">5</h3>
                  </div>
                  <h4 class="fw-bold my-4">Простой вход в профессию</h4>
                  <h6 class="mb-0">
                    Не нужен опыт и образование в IT. А если вы уже работали с 1С, вам будет проще перейти в программисты.
                  </h6>
                </div>
              </div>
            </swiper-slide>
          </swiper>
          </div>
          <div class="mt-5 my-xl-5 pt-xl-2"></div>
        </div>

    </section>
  </div>
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
      swipbreakpoints:{
        576:{
          slidesPerView: 1.5,
          centeredSlides: false
        },
        768:{
          slidesPerView: 1.8,
          centeredSlides: false
        },
        992:{
          slidesPerView: 1.4,
          centeredSlides: false
        },
        1200:{
          slidesPerView: 1.6,
          centeredSlides: false
        },
      }
    };
  },
}
</script>
<style>
.card2{
  height: 380px;
}
@media (max-width: 375px) {
  .card2{
    height: 510px;
  }
}
@media (min-width:375px) and (max-width: 410px) {
  .card2{
    height: 450px;
  }
}
@media (min-width:410px) and (max-width: 576px) {
  .card2{
    height: 390px;
  }
}
</style>