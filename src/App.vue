<template>
  <div class="page">
    <header class="navbar">
      <div class="navbar__top">
        <div class="top-left">
          <img :src="frameIcon" alt="Address" class="top-left__address-icon" />
          <span class="top-left__address-text">г. Москва, Скандинавский бульвар, д. 3, к.</span>
          <img :src="clockIcon" alt="Clock" class="top-left__time-icon" />
          <span class="top-left__time">с 9:00 до 22:00, без выходных</span>
        </div>
        <div class="top-right">
          <img :src="maxIcon" alt="Max" class="top-right__max-icon" />
          <span>MAX</span>
        </div>
        <img :src="mailIcon" alt="Mail" class="top-right__mail-icon" />
        <span class="top-right__email">welcome@kraskiremonta.ru</span>
      </div>
      <div class="navbar__divider"></div>

      <div class="navbar__bottom">
        <div class="logo">
          <img :src="colorIcon" alt="Color" class="logo__color" />
          <span class="logo__paint">КРАСКИ</span>
          <span class="logo__repair">РЕМОНТА</span>
        </div>

        <nav class="menu">
          <a href="#"><span>Компания</span><img :src="arrowIcon" alt="" class="menu__arrow" /></a>
          <a href="#"><span>Ремонт</span><img :src="arrowIcon" alt="" class="menu__arrow" /></a>
          <a href="#"><span>Дизайн</span><img :src="arrowIcon" alt="" class="menu__arrow" /></a>
          <a href="#"><span>Проектирование и инженерия</span><img :src="arrowIcon" alt="" class="menu__arrow" /></a>
          <a href="#"><span>Стоимость</span><img :src="arrowIcon" alt="" class="menu__arrow" /></a>
          <a href="#"><span>Портфолио</span><img :src="arrowIcon" alt="" class="menu__arrow" /></a>
        </nav>

        <div class="actions">
          <strong class="actions__phone">8 993 272 17 71</strong>
          <button type="button" class="actions__login">
            <span class="actions__login-text">Войти</span>
          </button>
        </div>
      </div>
    </header>
    <p class="breadcrumbs"><span class="breadcrumbs__muted">Главная</span> / <span>Проектирование и инженерия</span></p>
    <h1 class="hero-title">Проектирование и инженерия</h1>
    <p class="hero-description">
      Надежное проектирование  —  это основа безопасного и долговечного строительства. Мы выполняем полный цикл
      инженерно-технических работ: от обследования существующих зданий до выпуска рабочей документации и контроля
      реализации проекта. Главная цель  —  создать эффективные, технологичные и энергоэкономичные решения, соответствующие
      всем нормативам.
    </p>
    <img :src="mainImage" alt="Main image" class="hero-image" />
    <div class="hero-overlay"></div>
  </div>
</template>

<script setup>
import arrowIcon from "./assets/images/arrow.png";
import clockIcon from "./assets/images/clock.png";
import colorIcon from "./assets/images/color.png";
import frameIcon from "./assets/images/frame.png";
import maxIcon from "./assets/images/Max_logo_2025 1.png";
import mailIcon from "./assets/images/mail.png";
import mainImage from "./assets/images/main.jpg";
</script>

<style>
body {
  margin: 0;
}

.page {
  position: relative;
  width: 1920px;
}

.navbar {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 2;
  width: 1920px;
  height: 116px;
  opacity: 1;
  transform: rotate(0deg);
  background: #14172466;
  backdrop-filter: blur(30px);
  color: #ffffff;
  font-family: Arial, sans-serif;
}

.navbar__top {
  position: relative;
  height: 51px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 40px;
  font-size: 12px;
}

.navbar__divider {
  position: absolute;
  top: 51px;
  left: 0;
  width: 1920px;
  height: 0;
  opacity: 0.1;
  border: 1px solid #ffffff;
  box-sizing: border-box;
}

.top-left,
.top-right {
  display: flex;
  align-items: center;
  gap: 24px;
}

.top-right {
  position: absolute;
  top: 18px;
  left: 1562px;
  width: 60px;
  height: 20px;
  gap: 10px;
  opacity: 1;
  transform: rotate(0deg);
}

.top-right span {
  color: rgba(255, 255, 255, 0.7);
}

.top-right__max-icon {
  width: 20px;
  height: 20px;
  opacity: 1;
  transform: rotate(0deg);
  display: block;
}

.top-right__mail-icon {
  position: absolute;
  top: 18px;
  left: 1664px;
  width: 20px;
  height: 20px;
  opacity: 1;
  transform: rotate(0deg);
}

.top-right__email {
  position: absolute;
  top: 18px;
  left: 1694px;
  width: 168px;
  height: 20px;
  opacity: 1;
  transform: rotate(0deg);
  font-family: Inter, sans-serif;
  font-weight: 400;
  font-style: normal;
  font-size: 14px;
  line-height: 140%;
  letter-spacing: -0.05em;
  color: rgba(255, 255, 255, 0.7);
}

.top-left__address-icon {
  position: absolute;
  top: 16px;
  left: 58px;
  width: 20px;
  height: 20px;
  opacity: 1;
  transform: rotate(0deg);
}

.top-left__address-text {
  position: absolute;
  top: 16px;
  left: 88px;
  width: 263px;
  height: 20px;
  opacity: 1;
  transform: rotate(0deg);
  font-family: Inter, sans-serif;
  font-weight: 400;
  font-style: normal;
  font-size: 14px;
  line-height: 140%;
  letter-spacing: -0.05em;
  color: rgba(255, 255, 255, 0.7);
}

.top-left__time {
  position: absolute;
  top: 16px;
  left: 417px;
  width: 190px;
  height: 20px;
  opacity: 1;
  transform: rotate(0deg);
  font-family: Inter, sans-serif;
  font-weight: 400;
  font-style: normal;
  font-size: 14px;
  line-height: 140%;
  letter-spacing: -0.05em;
  color: rgba(255, 255, 255, 0.7);
}

.top-left__time-icon {
  position: absolute;
  top: 16px;
  left: 387px;
  width: 20px;
  height: 20px;
  opacity: 1;
  transform: rotate(0deg);
}

.navbar__bottom {
  height: 65px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 28px 0 24px;
}

.logo {
  position: absolute;
  top: 60px;
  left: 61px;
  width: 177.84078979492188px;
  height: 33.66769027709961px;
  opacity: 1;
  transform: rotate(0deg);
  display: flex;
  align-items: center;
  gap: 6px;
  font-weight: 700;
  letter-spacing: 0.02em;
  white-space: nowrap;
}

.logo__paint {
  background: #a0ce4e;
  color: #1d2b11;
  padding: 4px 8px;
  border-radius: 2px;
  font-size: 14px;
}

.logo__color {
  width: auto;
  height: 20px;
  display: block;
}

.logo__repair {
  color: #f3f3f3;
  font-size: 14px;
}

.menu {
  position: absolute;
  top: 69px;
  left: 322px;
  width: 1122px;
  height: 22px;
  opacity: 1;
  transform: rotate(0deg);
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 0;
  margin: 0;
}

.menu a {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  flex-shrink: 0;
  color: #ffffff;
  text-decoration: none;
  font-size: 14px;
  border-bottom: 1px solid rgba(255, 255, 255, 0.2);
  padding-bottom: 2px;
}

.menu__arrow {
  width: 12px;
  height: 6px;
  opacity: 1;
  transform: rotate(0deg);
}

.actions {
  position: absolute;
  top: 63px;
  left: 1558px;
  display: flex;
  align-items: flex-start;
  gap: 41px;
}

.actions__phone {
  position: relative;
  top: 6px;
  width: 111px;
  height: 22px;
  opacity: 1;
  transform: rotate(0deg);
  font-family: Inter, sans-serif;
  font-weight: 700;
  font-style: normal;
  font-size: 16px;
  line-height: 140%;
  letter-spacing: -0.05em;
  white-space: nowrap;
}

.actions__login {
  position: relative;
  width: 152px;
  height: 32px;
  opacity: 1;
  transform: rotate(0deg);
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
  padding: 10px;
  background: #96ce06;
  border: 0;
  color: #ffffff;
  box-sizing: border-box;
  cursor: pointer;
}

.actions__login-text {
  width: 46px;
  height: 22px;
  opacity: 1;
  transform: rotate(0deg);
  font-family: Inter, sans-serif;
  font-weight: 700;
  font-style: normal;
  font-size: 16px;
  line-height: 140%;
  letter-spacing: -0.05em;
}

.breadcrumbs {
  position: absolute;
  top: 207px;
  left: 58px;
  z-index: 3;
  width: 561px;
  height: 21px;
  display: flex;
  align-items: center;
  opacity: 1;
  transform: rotate(0deg);
  margin: 0;
  color: #ffffff;
  font-family: Inter, sans-serif;
  font-weight: 400;
  font-style: normal;
  font-size: 14px;
  line-height: 150%;
  letter-spacing: -0.05em;
  white-space: nowrap;
}

.breadcrumbs span {
  color: #ffffff;
  font-family: Inter, sans-serif;
  font-weight: 400;
  font-style: normal;
  font-size: 14px;
  line-height: 150%;
  letter-spacing: -0.05em;
}

.breadcrumbs span.breadcrumbs__muted {
  color: rgba(255, 255, 255, 0.7);
}

.hero-title {
  position: absolute;
  top: 275px;
  left: 58px;
  z-index: 3;
  display: inline-block;
  width: 868px;
  height: 80px;
  margin: 0;
  opacity: 1;
  transform: rotate(0deg) scaleX(0.8);
  transform-origin: left center;
  color: #ffffff;
  font-family: "Druk Cyr", sans-serif;
  font-weight: 700;
  font-style: normal;
  font-size: 65px;
  line-height: 100%;
  letter-spacing: -0.03em;
  text-transform: uppercase;
  white-space: nowrap;
}

.hero-description {
  position: absolute;
  top: 387px;
  left: 58px;
  z-index: 3;
  width: 689px;
  height: 120px;
  margin: 0;
  opacity: 1;
  transform: rotate(0deg);
  color: #ffffff;
  font-family: Inter, sans-serif;
  font-weight: 400;
  font-style: normal;
  font-size: 16px;
  line-height: 150%;
  letter-spacing: -0.05em;
}

.hero-image {
  display: block;
  width: 1920px;
  height: 630px;
  opacity: 1;
  transform: rotate(0deg);
  object-fit: cover;
  object-position: center 90%;
}

.hero-overlay {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1;
  width: 1920px;
  height: 630px;
  background: linear-gradient(265.33deg, rgba(20, 23, 36, 0) 40.42%, rgba(20, 23, 36, 0.6) 68.67%);
  pointer-events: none;
}
</style>
