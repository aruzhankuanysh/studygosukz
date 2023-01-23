<template>
  <router-view/>
</template>

<style>
@font-face {
  font-family: 'Gilroy-Regular ☞';
  font-style: normal;
  font-weight: normal;
  src: local('Gilroy-Regular ☞'), url('/public/fonts/Gilroy/Gilroy-Regular.woff') format('woff');
}
@font-face {
  font-family: 'Gilroy-Bold ☞';
  font-style: normal;
  font-weight: normal;
  src: local('Gilroy-Bold ☞'), url('/public/fonts/Gilroy/Gilroy-Bold.woff') format('woff');
}
*{
  margin: 0;
  padding: 0;
  font-family: 'Gilroy-Regular ☞';
}
.fw-bold, .fw-bolder{
  font-family: 'Gilroy-Bold ☞';
}
:root{
  --bs-primary: #65b2f0;
  --bs-primary-rgb: 101,178,240;
  --bs-gradient: linear-gradient(180deg, rgb(255 255 255 / 0%), rgb(255 255 255));
  --bs-success: #007b7f;
  --bs-success-rgb: 0, 123, 127;
  --bs-link-color: #ffffff;
  --bs-link-hover-color: #2d75af;
}
section{
  width: 100%;
  max-width: 1440px !important;
}
.hhh{
  height: 100% !important;
}
.btn-primary {
    --bs-btn-color: #fff;
    --bs-btn-bg: #65b2f0;
    --bs-btn-border-color: #65b2f0;
    --bs-btn-hover-color: #fff;
    --bs-btn-hover-bg: #3584c4;
    --bs-btn-hover-border-color: #4896d6;
    --bs-btn-focus-shadow-rgb: 49,132,253;
    --bs-btn-active-color: #fff;
    --bs-btn-active-bg: #4896d6;
    --bs-btn-active-border-color: #4896d6;
    --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
    --bs-btn-disabled-color: #fff;
    --bs-btn-disabled-bg: #65b2f0;
    --bs-btn-disabled-border-color: #65b2f0;
}
.btn-outline-primary {
  --bs-btn-color: #65b2f0;
  --bs-btn-border-color: #65b2f0;
  --bs-btn-hover-color: #fff;
  --bs-btn-hover-bg: #65b2f0;
  --bs-btn-hover-border-color: #65b2f0;
  --bs-btn-focus-shadow-rgb: 13,110,253;
  --bs-btn-active-color: #fff;
  --bs-btn-active-bg: #65b2f0;
  --bs-btn-active-border-color: #65b2f0;
  --bs-btn-active-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  --bs-btn-disabled-color: #65b2f0;
  --bs-btn-disabled-bg: transparent;
  --bs-btn-disabled-border-color: #65b2f0;
  --bs-gradient: none;
}
</style>
