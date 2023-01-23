<template>
  <main class="d-flex align-items-center flex-column">
    <HeaderMenu />
    <section class="row justify-content-center">
      <div class="col-11 col-xl-10 row position-relative"> 
        <div class="fixed-top">
          <div id="success" class="alert alert-success float-end col-10 col-sm-6 col-md-4 col-lg-3 mt-5 m-md-5 text-center" role="alert" style="display: none;"></div>
          <div id="danger" class="alert alert-danger        float-end col-10 col-sm-6 col-md-4 col-lg-3 mt-5 m-md-5 text-center" role="alert" style="display: none;"></div>
        </div>
        <div class="col-xl-6">
          <div class="my-xl-5 py-5"></div>
          <h1 class="fw-bold display-5">
            Освой профессию 
            <p class="d-inline text-primary fw-bold">1С&nbsp;-&nbsp;программиста</p> с&nbsp;нуля 
            всего за&nbsp;2&nbsp;месяца 
          </h1>
          <h3 class="mt-5 my-xl-5">Выйди на доход от&nbsp;250&nbsp;000&nbsp;тг&frasl;мес.</h3>
          <button class="btn btn-primary rounded-4 px-5 py-3 d-none d-xl-block" type="button" data-bs-toggle="modal" data-bs-target="#exampleModal1"><h4 class="m-0 mx-5">Записаться</h4></button>
          <div class="modal fade" id="exampleModal1" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
            <div class="modal-dialog modal-dialog-centered">
              <div class="modal-content p-4">
                <div class="modal-header pt-lg-3 pe-lg-4">
                  <h4 class="pe-lg-3 text-primary fw-bold">
                    Записаться на курс
                  </h4>
                  <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close" id="closeModalForm"></button>
                </div>
                <div class="modal-body mt-4 зе-2">
                  <form
                    class=""
                    id="tlgrm"
                  >
                    <div class="">
                      <input
                        class="form-control rounded-3"
                        type="text"
                        name="name"
                        placeholder="Ваше имя"
                        required
                      />
                    </div>
                    <div class=" mt-4 mt-lg-3">
                      <input
                        class="form-control rounded-3 tel"
                        type="text"
                        placeholder="Ваш номер телефона"
                        id="number"
                        name="number"
                        value=""
                        required
                      />
                    </div>
                    <div class="mt-4 mt-lg-3">
                      <input
                        class="form-control rounded-3"
                        type="email"
                        name="email"
                        placeholder="Email"
                        required
                      />
                    </div>
                    <div class="mt-4 mt-lg-3 text-start">
                      <div class="form-check">
                        <input class="form-check-input" type="checkbox" value="" id="flexCheckChecked" checked required>
                        <label class="form-check-label" for="flexCheckChecked">
                          Отправляя данные в данной форме вы соглашаетесь с обработкой персональных данных и политикой конфиденциальности
                        </label>
                      </div>
                    </div>
                    <button
                      class="btn btn-outline-primary text-uppercase py-3 rounded-pill mb-3 mt-4 col-12"
                      type="submit"
                      @click = "submited"
                    >
                      <h6 class="fw-bold m-0 mx-lg-3">
                        отправить заявку
                      </h6>
                    </button>
                  </form>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-6 p-0"><img class="img-fluid p-0" src="../assets/image1.png" alt=""></div>
        <div class="text-center d-xl-none">
          <button class="btn btn-primary rounded-4 px-5 py-3 col-12" type="button" data-bs-toggle="modal" data-bs-target="#exampleModal1">
            <h4 class="m-0 mx-5">
              Записаться
            </h4>
          </button>

          
        </div>
        <div>
          <div class="bg-primary bg-opacity-25 rounded-4 p-5">
            <div class="row px-xl-5">
              <div class="col-xl">
                <h3 class="fw-bold text-primary">
                  Когда
                </h3>
                <h4>
                  01 февраля
                </h4>
              </div>
              <div class="col-xl">
                <h3 class="fw-bold text-primary">
                  Формат
                </h3>
                <h4>
                  Оффлайн
                </h4>
              </div>
              <div class="col-xl">
                <h3 class="fw-bold text-primary">
                  Уровень
                </h3>
                <h4>
                  С нуля
                </h4>
              </div>
              <div class="col-xl">
                <h3 class="fw-bold text-primary">
                  Возможность
                </h3>
                <h4>
                  Трудоустройству
                </h4>
              </div>
    
            </div>
          </div>
        </div>
        <div class="my-5"></div>
        <div>
          <h1 class="fw-bold display-6">О профессии</h1>
          <h4 class="mt-5">
            1С разработчики помогают компаниям автоматизировать ежедневные задачи, считать налоги и&nbsp;зарплаты, вести документацию. Такие специалисты работают в программе 1С на встроенном языке программирования. Для удобства в нём можно писать как на английском, так и на русском.
            <br />
            <br />
            1С-разработчики настраивают конфигурации, консультируют сотрудников, подключают 1С к сервисам компании. Можно работать в фирме любого масштаба — от ИП до крупной промышленной компании.
          </h4>
        </div>
        <div class="my-5"></div>
        <Cards1 />
        <div class="my-5"></div>
      </div>
    </section>
    <Cards2 />
    <IfYou />
    <div class="container-fluid bg-primary bg-opacity-25 row justify-content-center p-0">
      <section class="row justify-content-center position-relative my-5 p-0">
        <div class="col-11 col-xl-10 row align-items-center">
          <div class="col-xl-7">
            <h1 class="fw-bold">
              Освойте профессию 1С&nbsp;&#8209;&nbsp;программиста с&nbsp;нуля
            </h1>
            <h4 class="text-primary fw-bold my-5">
              И начните поиск работы уже через 7 месяцев 
            </h4>
            <div class="d-xl-none">
              <img class="img-fluid" src="../assets/image7.png" alt="">
            </div>
            <button class="btn btn-primary rounded-4 px-5 py-3 col-12 col-xl-7" type="button" data-bs-toggle="modal" data-bs-target="#exampleModal1">
              <h4 class="m-0 fw-bold">
                Записаться на курс
              </h4>
            </button>
          </div>
          <div class="col-5 d-none d-xl-block">
            <img class="img-fluid" src="../assets/image7.png" alt="">
          </div>
        </div>
      </section>
    </div>
    <div class="py-5" id="about"></div>
    <section class="row justify-content-center position-relative">
      <AboutCourse />
      <div class="py-5" id="programm"></div>
      <ProgrammCourse />
    </section>
    <div class="container-fluid bg-primary bg-opacity-25 row justify-content-center p-0">
      <section class="row justify-content-center position-relative p-0">
        <div class="col-11 col-xl-10 row align-items-center py-5 py-xl-0">
          <div class="col-xl-6">
            <h3 class="fw-bold">
              После обучения вашего уровня знаний и навыков будет достаточно для прохождения сертификации «1С Профессионал», а также для подготовки к сдаче экзамена «1С Специалист по платформе»
            </h3>
          </div>
          <div class="col-xl-6">
            <img class="img-fluid pe-5 pe-xl-0" src="../assets/image8.png" alt="">
          </div>
        </div>
      </section>
    </div>
    <div class="py-5" id="price"></div>
  
    <PriceCourse />
    
    <Resume />

    <div class="my-5"></div>

    <Questions />
    
    <div class="container-fluid bg-primary bg-opacity-25 row justify-content-center p-0" id="more">
      <section class="row justify-content-center position-relative p-0">
        <div class="col-11 col-xl-10 py-4">
          <h1 class="fw-bold mb-5">Получите подробную информацию</h1>
          <form id="tg" class="row align-items-center">
            <div>
              <div class="form-check mb-3">
                <input class="form-check-input" type="checkbox" value="" id="flexCheckChecked" checked required>
                <label class="form-check-label" for="flexCheckChecked">
                  Отправляя данные в данной форме вы соглашаетесь с обработкой персональных данных и политикой конфиденциальности
                </label>
              </div>
            </div>
            <div class="col-xl-3 mb-4">
              <input type="text" class="form-control-lg form-control" name="name" placeholder="Имя">
            </div>
            <div class="col-xl-3 mb-4">
              <input type="text" class="form-control-lg form-control tel" name="number" placeholder="+7 (999)999-99-99" value="">
            </div>
            <div class="col-xl-3 mb-4">
              <input type="email" class="form-control-lg form-control" name="email" placeholder="E-mail">
            </div>
            <div class="col-xl-3 mb-4">
              <input type="submit" class="form-control-lg form-control btn btn-primary fw-bold" placeholder="Отправить" @click="study">
            </div>
          </form>
        </div>
      </section>
    </div>
  
    <FooterV />
  </main>
</template>

<script>
import HeaderMenu from '@/components/HeaderMenu.vue'
import Cards1 from '@/components/Cards1.vue'
import Cards2 from '@/components/Cards2.vue'
import IfYou from '@/components/IfYou.vue'
import AboutCourse from '@/components/AboutCourse.vue'
import ProgrammCourse from '@/components/ProgrammCourse.vue'
import PriceCourse from '@/components/PriceCourse.vue'
import Resume from '@/components/Resume.vue'
import Questions from '@/components/Questions.vue'
import FooterV from '@/components/FooterView.vue'

import axios from 'axios'

export default {
  name: 'HomeView',
  components: {
    HeaderMenu,
    Cards1,
    Cards2,
    IfYou,
    AboutCourse,
    ProgrammCourse,
    PriceCourse,
    Resume,
    Questions,
    FooterV
  },
  methods:{
    async submited(){
      const TOKEN = "5638911701:AAEnc9OAGEDCPbWknEup9RFjLIVunC64I7M";
      const CHAT_ID = "-1001882975999";
      const URI_API = `https://api.telegram.org/bot${ TOKEN }/sendMessage`
      const success = document.getElementById('success');
      const danger = document.getElementById('danger');


      document.getElementById('tlgrm').addEventListener('submit', function(e) {
        e.preventDefault();
        let message = ` Заявка обучение 1C \n`;
        message+= `<b>Отправитель: </b> ${this.name.value}\n`;
        message+= `<b>Номер: </b> ${this.number.value}\n`;
        message+= `<b>Почта: </b> ${this.email.value}\n`;
        console.log(message)

        axios.post(URI_API, {
          chat_id: CHAT_ID,
          parse_mode: 'html',
          text: message
        })// eslint-disable-next-line
        .then((res) =>{
          this.name.value = "";
          this.email.value = ""
          this.number.value = "";
          success.innerHTML = 'Заявка отправлена успешно!';
          success.style.display = 'block';
          setTimeout(function(){
            document.getElementById('success').style.display = 'none';
          }, 3000 );
          document.getElementById('closeModalForm').click();
        })
        .catch((err) =>{
          console.warn(err)
          danger.innerHTML = 'Ошибка отправки!';
          danger.style.display = 'block';
          setTimeout(function(){
            document.getElementById('danger').style.display = 'none';
          }, 3000 );
        })
        .finally(() => {
          console.log('END')
        })
      })
    },
    async study(){
      const TOKEN = "5638911701:AAEnc9OAGEDCPbWknEup9RFjLIVunC64I7M";
      const CHAT_ID = "-1001882975999";
      const URI_API = `https://api.telegram.org/bot${ TOKEN }/sendMessage`
      const successs = document.getElementById('success');
      const dangers = document.getElementById('danger');


      document.getElementById('tg').addEventListener('submit', function(e) {
        e.preventDefault();
        let message = ` Узнать подробнее обучение 1C \n`;
        message+= `<b>Отправитель: </b> ${this.name.value}\n`;
        message+= `<b>Номер: </b> ${this.number.value}\n`;
        message+= `<b>Почта: </b> ${this.email.value}\n`;
        console.log(message)

        axios.post(URI_API, {
          chat_id: CHAT_ID,
          parse_mode: 'html',
          text: message
        })// eslint-disable-next-line
        .then((res) =>{
          this.name.value = "";
          this.email.value = ""
          this.number.value = "";
          successs.innerHTML = 'Заявка отправлена успешно!';
          successs.style.display = 'block';
          setTimeout(function(){
            document.getElementById('successs').style.display = 'none';
          }, 3000 );
          document.getElementById('closeModalForm').click();
        })
        .catch((err) =>{
          console.warn(err)
          dangers.innerHTML = 'Ошибка отправки!';
          dangers.style.display = 'block';
          setTimeout(function(){
            document.getElementById('dangers').style.display = 'none';
          }, 3000 );
        })
        .finally(() => {
          console.log('END')
        })
      })
    }
   },
   mounted(){
    window.addEventListener("DOMContentLoaded", function() {
      [].forEach.call( document.querySelectorAll('.tel'), function(input) {
      var keyCode;
      function mask(event) {
          event.keyCode && (keyCode = event.keyCode);
          var pos = this.selectionStart;
          if (pos < 3) event.preventDefault();
          var matrix = "+7 (___) ___ ____",
              i = 0,
              def = matrix.replace(/\D/g, ""),
              val = this.value.replace(/\D/g, ""),
              new_value = matrix.replace(/[_\d]/g, function(a) {
                  return i < val.length ? val.charAt(i++) || def.charAt(i) : a
              });
          i = new_value.indexOf("_");
          if (i != -1) {
              i < 5 && (i = 3);
              new_value = new_value.slice(0, i)
          }
          var reg = matrix.substr(0, this.value.length).replace(/_+/g,
              function(a) {
                  return "\\d{1," + a.length + "}"
              }).replace(/[+()]/g, "\\$&");
          reg = new RegExp("^" + reg + "$");
          if (!reg.test(this.value) || this.value.length < 5 || keyCode > 47 && keyCode < 58) this.value = new_value;
          if (event.type == "blur" && this.value.length < 5)  this.value = ""
      }
      input.addEventListener("input", mask, false);
      input.addEventListener("focus", mask, false);
      input.addEventListener("blur", mask, false);
      input.addEventListener("keydown", mask, false)
      });

    });
  }
}
</script>
<style>
.price{
  background-image: url(../assets/elemPricePrimary.png);
  background-size: contain;
  background-repeat: no-repeat;
}
.price2{
  background-image: url(../assets/elemPriceWhite.png);
  background-size: contain;
  background-repeat: no-repeat;
}
li{
  margin-bottom: 8px;
}
</style>
