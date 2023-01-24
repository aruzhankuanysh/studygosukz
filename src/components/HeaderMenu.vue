<template>
  <div class="container-fluid d-flex justify-content-center sticky-top bg-light p-0">
    <section class="row justify-content-center sticky-top">
      <nav class="navbar navbar-expand-lg col-11 col-xl-10 px-4">
        <div class="container-fluid p-0">
          <a class="navbar-brand col-1" href="/">
            <img 
              class="img-fluid col-sm-9 col-md-6 col-lg-4" 
              src="../assets/logoOrigBPC.png" 
              alt=""
            >
          </a>
          <button 
            class="navbar-toggler" 
            type="button" 
            data-bs-toggle="offcanvas" 
            data-bs-target="#offcanvasNavbar" 
            aria-controls="offcanvasNavbar" 
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="offcanvas offcanvas-end" 
            tabindex="-1" 
            id="offcanvasNavbar" 
            aria-labelledby="offcanvasNavbarLabel"
            >
            <div class="offcanvas-header">
              <div class="d-flex align-items-center">
                <img 
                class="img-fluid col-1 me-3" 
                src="../assets/logoOrigBPC.png" 
                alt=""
                >
                <h4 class="offcanvas-title fw-bold" id="offcanvasNavbarLabel">Компания</h4>
              </div>
              <button id="closemodal" type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
            </div>
            <div class="offcanvas-body">
              <ul class="navbar-nav me-auto my-2 my-lg-0">
                <li class="nav-item">
                  <h5>
                    <a class="nav-link active undrln ttt" href="/#about">
                      О курсе
                    </a>
                  </h5>
                </li>
                <li class="nav-item">
                  <h5>
                    <a class="nav-link undrln ttt" href="/#programm">
                      Программа курса
                    </a>
                  </h5>
                </li>
                <li class="nav-item">
                  <h5>
                    <a class="nav-link undrln ttt" href="/#price">
                      Цена
                    </a>
                  </h5>
                </li>
                <li class="nav-item">
                  <h5>
                    <a class="nav-link undrln ttt" href="#reviews">
                      Отзывы
                    </a>
                    </h5>
                </li>
                <li class="nav-item">
                  <h5>
                    <a class="nav-link undrln ttt" href="#more">
                      Получить консультацию
                    </a>
                  </h5>
                </li>
              </ul>
              <div className="d-flex align-items-center justify-content-evenly">
                <!-- <select class="form-select" v-model="select">
                  <option value="ru">ru</option>
                  <option value="kaz">kaz</option>
                  <option value="en">en</option>
                </select> -->
                <div class="border rounded-2 ms-4 px-4 py-1" id="lang" @click="switchLang">ru</div>
              </div>
            </div>
          </div>
        </div>
      </nav>
    </section>
  </div>
 
</template>
<script setup>

</script>
<style>
.undrln{
  text-decoration: none;
}
.undrln:hover{
  text-decoration: underline;
}
</style>

