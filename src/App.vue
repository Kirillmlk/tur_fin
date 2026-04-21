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
    <p class="breadcrumbs"><span class="breadcrumbs__muted">Главная / </span><span>Проектирование и инженерия</span></p>
    <h1 class="hero-title">Проектирование и инженерия</h1>
    <p class="hero-description">
      Надежное проектирование  —  это основа безопасного и долговечного строительства. Мы выполняем полный цикл
      инженерно-технических работ: от обследования существующих зданий до выпуска рабочей документации и контроля
      реализации проекта. Главная цель  —  создать эффективные, технологичные и энергоэкономичные решения, соответствующие
      всем нормативам.
    </p>
    <img :src="mainImage" alt="Main image" class="hero-image" />
    <div class="hero-overlay"></div>
    <section class="next-block">
      <div class="service-row">
        <div class="service-intro service-intro--offset">
          <h2 class="service-intro__title--research">Исследование зданий</h2>
          <p class="service-intro__text--research">
            Перед началом любого проектирования мы проводим тщательное обследование объекта. Это позволяет определить
            текущее состояние конструкций и избежать ошибок при разработке.
          </p>
        </div>
        <div class="service-content service-content--right">
          <div class="service-cards">
            <article class="service-card">
              <h3>01</h3>
              <p>Инструментальное обследование несущих элементов</p>
            </article>
            <article class="service-card">
              <h3>02</h3>
              <p>Диагностика инженерных систем и коммуникаций</p>
            </article>
            <article class="service-card">
              <h3>03</h3>
              <p>Анализ технического состояния и деформаций</p>
            </article>
            <article class="service-card">
              <h3>04</h3>
              <p>Подготовка отчета с рекомендациями по усилению или замене конструкций</p>
            </article>
          </div>
          <div class="service-result">
            <strong>📍 РЕЗУЛЬТАТ</strong>
            <span>Точное понимание потенциала здания и отсутствие сюрпризов на этапе стройки</span>
          </div>
        </div>
      </div>

      <div class="service-row service-row--reverse">
        <div class="service-content service-content--left">
          <div class="service-cards">
            <article class="service-card">
              <h3>01</h3>
              <p>Архитектурные решения и визуализации фасадов</p>
            </article>
            <article class="service-card">
              <h3>02</h3>
              <p>Конструктивные схемы и расчеты нагрузок</p>
            </article>
            <article class="service-card">
              <h3>03</h3>
              <p>Электрика, отопление, вентиляция, водоснабжение, канализация</p>
            </article>
            <article class="service-card">
              <h3>04</h3>
              <p>3D и BIM-моделирование для точного планирования и смет</p>
            </article>
          </div>
          <div class="service-result">
            <strong>📍 РЕЗУЛЬТАТ</strong>
            <span>Полный комплект документов, который позволяет вести строительство без задержек и изменений</span>
          </div>
        </div>
        <div class="service-intro service-intro--offset">
          <h2>Проектирование</h2>
          <p class="service-intro__text--research">
            На этом этапе мы превращаем концепцию в рабочую документацию, по которой можно строить без доработок и
            уточнений. Мы разрабатываем проекты жилых, общественных и коммерческих зданий, а также инженерные системы
            любой сложности.
          </p>
        </div>
      </div>

      <div class="service-row service-row--management">
        <div class="service-intro service-intro--offset">
          <h2>Управление строительством</h2>
          <p class="service-intro__text--research">
            Управление строительством — это комплексное сопровождение проекта от начала до ввода объекта в эксплуатацию.
            Мы берем на себя организацию всех процессов.
          </p>
        </div>
        <div class="service-content service-content--right">
          <div class="service-cards">
            <article class="service-card">
              <h3>01</h3>
              <p>Координация подрядчиков и поставщиков</p>
            </article>
            <article class="service-card">
              <h3>02</h3>
              <p>Контроль сроков и качества</p>
            </article>
            <article class="service-card">
              <h3>03</h3>
              <p>Ведение графиков, отчетов и бюджетов</p>
            </article>
            <article class="service-card">
              <h3>04</h3>
              <p>Оперативное решение технических вопросов</p>
            </article>
          </div>
          <div class="service-result">
            <strong>📍 РЕЗУЛЬТАТ</strong>
            <span>Строительство без хаоса, перерасходов и переделок</span>
          </div>
        </div>
      </div>

      <div class="service-row service-row--reverse">
        <div class="service-content">
          <div class="service-cards">
            <article class="service-card">
              <h3>01</h3>
              <p>Проверка соответствия строительных работ проекту</p>
            </article>
            <article class="service-card">
              <h3>02</h3>
              <p>Контроль смет, актов и материалов</p>
            </article>
            <article class="service-card">
              <h3>03</h3>
              <p>Приемка скрытых работ</p>
            </article>
            <article class="service-card">
              <h3>04</h3>
              <p>Фотоотчеты и акты по каждому визиту</p>
            </article>
          </div>
          <div class="service-result">
            <strong>📍 РЕЗУЛЬТАТ</strong>
            <span>Объект построен точно по проекту и с гарантированным качеством</span>
          </div>
        </div>
        <div class="service-intro service-intro--offset">
          <h2>Технический надзор</h2>
          <p class="service-intro__text--research">
            Мы контролируем каждый этап реализации проекта, чтобы все выполнялось строго по чертежам и нормативам.
            Наши специалисты регулярно выезжают на объект, проверяют качество работ, материалов и технологий.
          </p>
        </div>
      </div>
    </section>
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
@font-face {
  font-family: "Druk Cyr";
  src: local("Druk Cyr"), local("Druk Cyr Bold"), local("DrukCyr-Bold");
  font-weight: 700;
  font-style: normal;
}

html,
body {
  width: 100%;
}

body {
  margin: 0;
  background: #eff1f4;
  overflow-x: hidden;
}

.page {
  --page-scale: min(1, calc(100vw / 1920));
  position: relative;
  width: 1920px;
  min-height: 2200px;
  margin: 0;
  transform: scale(var(--page-scale));
  transform-origin: top left;
  overflow: hidden;
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
  margin-right: 6px;
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

.next-block {
  position: absolute;
  top: 730px;
  left: 58px;
  width: 1804px;
  height: 1428px;
  opacity: 1;
  transform: rotate(0deg);
  background: #eff1f4;
  box-sizing: border-box;
  padding: 18px 0;
  display: grid;
  gap: 16px;
}

.service-row {
  position: relative;
  display: grid;
  grid-template-columns: 530px 1fr;
  gap: 16px;
  padding: 0 0 8px;
}

.service-row--reverse {
  grid-template-columns: 1fr 530px;
}

.service-row--management {
  grid-template-columns: 530px 1196px;
  justify-content: space-between;
}

.service-intro {
  padding: 26px 12px 0 0;
}

.service-intro--offset {
  margin-top: 88px;
}

.service-intro h2 {
  margin: 0 0 12px;
  font-family: "Druk Cyr", sans-serif;
  font-size: 28px;
  line-height: 1;
  letter-spacing: -0.02em;
  text-transform: uppercase;
  color: #141724;
}

.service-intro__title--research {
  position: static;
  width: 100%;
  height: auto;
  margin: 0 0 16px;
  opacity: 1;
  transform: rotate(0deg);
  font-family: "Druk Cyr", sans-serif;
  font-weight: 700;
  font-style: normal;
  font-size: 48px;
  line-height: 100%;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  white-space: nowrap;
}

.service-intro p {
  position: static;
  width: 100%;
  max-width: 100%;
  height: auto;
  margin-top: 32px;
  opacity: 1;
  transform: rotate(0deg);
  font-family: Inter, sans-serif;
  font-weight: 400;
  font-style: normal;
  font-size: 16px;
  line-height: 150%;
  letter-spacing: -0.05em;
  color: #141724;
  overflow-wrap: anywhere;
  word-break: break-word;
}

.service-intro__text--research {
  margin-top: 32px;
  width: 480px;
  height: 72px;
  max-width: 100%;
}

.service-content {
  width: 1196px;
  padding-right: 0;
  box-sizing: border-box;
}

.service-content--right {
  justify-self: end;
  margin: 0;
  display: flex;
  flex-direction: column;
  align-items: flex-end;
}

.service-content--left {
  justify-self: start;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

.service-cards {
  width: 1196px;
  display: grid;
  grid-template-columns: repeat(4, 284px);
  column-gap: 20px;
  row-gap: 10px;
}

.service-card {
  width: 284px;
  height: 146px;
  background: #f7f8fa;
  padding: 12px 14px;
  box-sizing: border-box;
}

.service-card h3 {
  margin: 0 0 8px;
  width: 24px;
  height: 36px;
  opacity: 1;
  transform: rotate(0deg);
  font-family: "Druk Cyr", sans-serif;
  font-weight: 700;
  font-style: normal;
  font-size: 36px;
  line-height: 100%;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  color: #5f3df2;
}

.service-card p {
  margin: 0;
  font-family: Inter, sans-serif;
  font-size: 13px;
  line-height: 130%;
  letter-spacing: -0.02em;
  color: #1b2231;
  overflow-wrap: anywhere;
  word-break: break-word;
}

.service-result {
  margin-top: 10px;
  width: 1196px;
  height: 116px;
  opacity: 1;
  transform: rotate(0deg);
  background: #96ce06;
  display: flex;
  align-items: center;
  gap: 22px;
  padding: 8px 14px;
  box-sizing: border-box;
}

.service-result strong {
  width: 236px;
  height: 48px;
  opacity: 1;
  transform: rotate(0deg);
  font-family: "Druk Cyr", sans-serif;
  font-weight: 700;
  font-style: normal;
  font-size: 30px;
  line-height: 100%;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  color: #101625;
  white-space: nowrap;
}

.service-result span {
  width: 369px;
  height: 38px;
  max-width: 100%;
  font-family: Inter, sans-serif;
  font-size: 14px;
  line-height: 130%;
  letter-spacing: -0.02em;
  color: #1c242e;
  overflow-wrap: anywhere;
  word-break: break-word;
}
</style>
