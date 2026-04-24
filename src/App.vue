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
          <img :src="mainLogo" alt="Main logo" class="logo__main" />
        </div>

        <nav class="menu">
          <a href="#"><span>Компания</span><img :src="arrowIcon" alt="" class="menu__arrow" /></a>
          <a href="#"><span>Ремонт</span><img :src="arrowIcon" alt="" class="menu__arrow" /></a>
          <a href="#"><span>Дизайн</span><img :src="arrowIcon" alt="" class="menu__arrow" /></a>
          <a href="#"><span>Проектирование и инженерия</span><img :src="arrowIcon" alt="" class="menu__arrow" /></a>
          <a href="#"><span>Стоимость</span><img :src="arrowIcon" alt="" class="menu__arrow" /></a>
          <a href="#"><span>Портфолио</span><img :src="arrowIcon" alt="" class="menu__arrow" /></a>
          <div class="menu__contacts">
            <a href="#" @click.prevent="contactsMenuOpen = !contactsMenuOpen">
              <span>Контакты</span><img :src="arrowIcon" alt="" class="menu__arrow" />
            </a>
            <div v-show="contactsMenuOpen" class="menu__contacts-dropdown">
              <div class="menu__contacts-row">
                <img :src="frameIcon" alt="Address" class="menu__contacts-icon" />
                <span>г. Москва, Скандинавский бульвар, д. 3, к.</span>
              </div>
              <div class="menu__contacts-row">
                <img :src="clockIcon" alt="Clock" class="menu__contacts-icon" />
                <span>с 9:00 до 22:00, без выходных</span>
              </div>
              <div class="menu__contacts-row">
                <img :src="mailIcon" alt="Mail" class="menu__contacts-icon" />
                <span>welcome@kraskiremonta.ru</span>
              </div>
              <div class="menu__contacts-row">
                <img :src="maxIcon" alt="Max" class="menu__contacts-icon" />
                <span>MAX</span>
              </div>
            </div>
          </div>
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
    <h2 class="team-title">Команда под проект</h2>
    <section class="team-block">
      <div class="team-grid">
        <article class="team-member">
          <img :src="teamImg1" alt="Павел" class="team-member__photo" />
          <span class="team-member__role">Главный инженер</span>
          <h3 class="team-member__name">Павел</h3>
          <p class="team-member__desc">Отвечает за согласованность всех разделов</p>
        </article>

        <article class="team-member">
          <img :src="teamImg2" alt="Алина" class="team-member__photo" />
          <span class="team-member__role">Конструктор</span>
          <h3 class="team-member__name">Алина</h3>
          <p class="team-member__desc">Проектирует надежные и безопасные несущие системы</p>
        </article>

        <article class="team-member">
          <img :src="teamImg3" alt="Иван" class="team-member__photo" />
          <span class="team-member__role">Инженер</span>
          <h3 class="team-member__name">Иван</h3>
          <p class="team-member__desc">Разрабатывает коммуникации и инженерные решения</p>
        </article>

        <article class="team-member">
          <img :src="teamImg4" alt="Антон" class="team-member__photo" />
          <span class="team-member__role">Менеджер проекта</span>
          <h3 class="team-member__name">Антон</h3>
          <p class="team-member__desc">Координирует процессы и контролирует сроки</p>
        </article>

        <article class="team-member">
          <img :src="teamImg5" alt="Семен" class="team-member__photo" />
          <span class="team-member__role">Технический надзор</span>
          <h3 class="team-member__name">Семен</h3>
          <p class="team-member__desc">Следит за соответствием проекта и качества исполнения</p>
        </article>
      </div>
    </section>
    <h2 class="why-title">Почему выбирают нас</h2>
    <p class="why-text">
      Мы создаем проекты, которые можно строить без доработок — надежно, технологично и с гарантированным результатом.
      Проектирование с нами — это уверенность в том, что здание будет работать десятилетиями.
    </p>
    <section class="why-cards">
      <article class="why-card why-card--active">
        <span class="why-card__num">01</span>
        <h3 class="why-card__title">Соответствие нормам</h3>
        <p class="why-card__text">
          Работаем по действующим СНиП и СП, учитывая все требования и согласования на каждом этапе проектирования.
        </p>
      </article>
      <article class="why-card">
        <span class="why-card__num">02</span>
        <h3 class="why-card__title">Точность и экономика</h3>
        <p class="why-card__text">
          Обеспечиваем точные расчеты, рациональное использование материалов и оптимизацию бюджета без потери качества.
        </p>
      </article>
      <article class="why-card">
        <span class="why-card__num">03</span>
        <h3 class="why-card__title">Современные технологии</h3>
        <p class="why-card__text">
          Используем актуальные инженерные решения и BIM-проектирование для точного моделирования и контроля всех процессов.
        </p>
      </article>
      <article class="why-card">
        <span class="why-card__num">04</span>
        <h3 class="why-card__title">Полное сопровождение</h3>
        <p class="why-card__text">
          Ведем проект от концепции до ввода объекта в эксплуатацию, обеспечивая стабильный результат и качество на каждом этапе.
        </p>
      </article>
    </section>
    <section class="next-large-block">
      <footer class="mega-footer">
        <div class="mega-footer__top">
          <div class="mega-footer__brand">
            <img :src="kraskiLogo" alt="Краски Ремонта" class="mega-footer__brand-logo" />
          </div>
          <div class="mega-footer__contacts">
            <span class="mega-footer__address">
              <img :src="footerAddressIcon" alt="" class="mega-footer__address-icon" />
              <span class="mega-footer__address-text">г. Москва, Скандинавский бульвар, д. 3, к.</span>
            </span>
            <span class="mega-footer__email">
              <img :src="footerEmailIcon" alt="" class="mega-footer__address-icon" />
              <span>welcome@kraskiremonta.ru</span>
            </span>
            <span class="mega-footer__phone">8 993 272 17 71</span>
            <span class="mega-footer__max">
              <img :src="footerMaxIcon" alt="MAX" class="mega-footer__address-icon" />
              <span class="mega-footer__max-text">MAX</span>
            </span>
          </div>
        </div>

        <div class="mega-footer__links mega-footer__links--main">
          <div class="mega-footer__col">
            <h4>Компания</h4>
            <a href="#">О нас</a>
            <a href="#">Социальная ответственность</a>
            <a href="#">Карьера</a>
            <a href="#">Партнерам</a>
            <a href="#">Юридическое сопровождение</a>
            <a href="#">Блог</a>
            <a href="#">Контакты</a>
          </div>

          <div class="mega-footer__col">
            <h4>Ремонт жилых помещений</h4>
            <a href="#">Квартиры,</a>
            <a href="#">Коттеджи</a>
            <a href="#">Таунхаусы</a>
            <a href="#">Загородный дом</a>
            <a href="#">Этапы работ</a>
            <a href="#">Контроль за ремонтом</a>
            <a href="#">Гарантия и страхование ремонта</a>
          </div>

          <div class="mega-footer__col">
            <h4>Ремонт коммерческих помещений</h4>
            <a href="#">Офисы</a>
            <a href="#">Отели</a>
            <a href="#">Магазины</a>
            <a href="#">Фитнес-центры</a>
            <a href="#">Склады</a>
            <a href="#">Салоны красоты</a>
            <a href="#">Рестораны и кафе</a>
            <a href="#">Медицинские центры</a>
          </div>

          <div class="mega-footer__col">
            <h4>Дизайн</h4>
            <a href="#">Архитектура и дизайн</a>
            <a href="#">Жилые интерьеры</a>
            <a href="#">Интерьеры для бизнеса</a>
            <a href="#">Авторские надзоры</a>
            <a href="#">Подбор материалов</a>
            <a href="#">Меблировка и комплектация</a>
          </div>
        </div>

        <div class="mega-footer__links mega-footer__links--second">
          <div class="mega-footer__col">
            <h4>Проектирование и инженерия</h4>
            <a href="#">Инженерные проекты</a>
            <a href="#">Управление строительством</a>
            <a href="#">Промышленное проектирование</a>
            <a href="#">Обследование зданий</a>
            <a href="#">Команда под проект</a>
            <a href="#">Технический надзор</a>
          </div>

          <div class="mega-footer__col">
            <h4>Стоимость</h4>
            <a href="#">Ремонт под ключ</a>
            <a href="#">Архитектура и дизайн</a>
            <a href="#">Проектирование и инженерия</a>
            <a href="#">Прайс лист</a>
          </div>

          <div class="mega-footer__col">
            <h4>Портфолио</h4>
            <a href="#">Фотографии жилого интерьера</a>
            <a href="#">Фотографии коммерческого интерьера</a>
            <a href="#">Видео-обзоры объектов</a>
          </div>

          <div class="mega-footer__cabinet">
            <img :src="footerLkIcon" alt="" class="mega-footer__lk-icon" />
            <span>Личный кабинет</span>
          </div>
        </div>

        <div class="mega-footer__bottom">
          <div class="mega-footer__bottom-row">
            <span>© 2004-2025 «Краски Ремонта»</span>
            <span>Правила организации выполнения работ по ремонту</span>
            <span></span>
            <span>ООО «ДОМЕО МАРКЕТИНГ»<br />ИНН 9704067054<br />ОГРН 1217700244717</span>
          </div>
          <div class="mega-footer__bottom-row mega-footer__bottom-row--links">
            <span>Публичная оферта</span>
            <span>«Покупка со сбером» в кредит</span>
            <span></span>
            <span></span>
          </div>
          <div class="mega-footer__bottom-row mega-footer__bottom-row--links">
            <span>Политика конфиденциальности</span>
            <span>Оплата</span>
            <span></span>
            <span></span>
          </div>
          <div class="mega-footer__bottom-row mega-footer__bottom-row--links">
            <span>Правовая информация</span>
            <span></span>
            <span></span>
            <span></span>
          </div>
        </div>

        <div class="mega-footer__legal-text">
          <p>
            Обработка персональных данных Пользователя осуществляется в соответствии с законодательством Российской Федерации.
            Администрация Сайта обрабатывает персональные данные Пользователя в целях осуществления обратной связи. Заполняя форму
            "Фамилия, Имя, Отчество", "Электронная почта", "Телефон", "Город" и иные сведения, Пользователь дает согласие на
            обработку своих персональных данных - имени, адреса электронной почты и телефона. Под обработкой персональных данных
            понимается сбор, систематизация, накопление, уточнение (обновление, изменение).
          </p>
          <p>
            Вся информация, размещенная на данном сайте, включая стоимости товаров и (или) услуг, ни при каких условиях не является
            офертой, публичной офертой, договором и публичным договором определяемыми положениями статьей 426, 435 и 437 и 494 ГК РФ
            или заверениями об обязательствах. Любая информация, представленная на данном сайте, носит исключительно информационный
            характер. Информация о технологиях и иных качественных характеристиках услуг, указанных на сайте, может быть изменена
            производителем без предварительного уведомления. Фактические характеристики, цена, внешний вид товара или услуги могут
            отличаться от тех, что были указаны на любой странице сайта в момент оформления заказа, заявки или подписания договора с
            компанией. Все материалы и информация, размещенные на данном веб-ресурсе, представлены исключительно в информационных
            целях. Веб-ресурс не несет ответственности за достоверность, полноту или актуальность представленной информации. Информация,
            размещенная на веб-ресурсе, не может служить как юридическое доказательство или как основание для подачи судебных исков.
            Полные условия сотрудничества вы можете найти в договоре, который заключили с компанией. Для получения подробной информации,
            пожалуйста, свяжитесь с менеджерами компании, по указанным на сайте телефонам или через формы обратной связи. Вы можете
            ознакомиться с <span class="mega-footer__legal-link">политикой правил работы сайта</span>.
          </p>
          <p>
            Администрация сайта обязуется сохранять Вашу конфиденциальность в сети Интернет.
            <span class="mega-footer__legal-link">Политика Конфиденциальности</span> компании рассказывает о том, как собираются,
            обрабатываются и хранятся Ваши личные данные. Администрация уделяет большое внимание защите личной информации пользователей.
            Пользуясь сайтом <span class="mega-footer__legal-link">domeo.ru</span>, пользователь тем самым дает согласие на применение
            правил сбора и использования данных, изложенных в настоящем документе. Если Вы не согласны с условиями нашей
            <span class="mega-footer__legal-link">политики конфиденциальности</span>, не используйте сайт
            <span class="mega-footer__legal-link">domeo.ru</span>.
          </p>
          <p>
            1. Под "идеальным" понимается результат, тождественный ожиданиям клиента, воспроизведенный 1:1 по выбранному эталонному
            образцу и подтвержденный договорными обязательствами;
          </p>
          <p>
            2. Согласно исследованию рынка оказания услуг по капитальному ремонту и дизайну помещений, проведенного исследовательской
            компанией Конкол (ИНН 9701073853) в 2025 год.
          </p>
        </div>
      </footer>
    </section>
  </div>
</template>

<script setup>
import { ref } from "vue";
import arrowIcon from "./assets/images/arrow.png";
import clockIcon from "./assets/images/clock.png";
import frameIcon from "./assets/images/frame.png";
import maxIcon from "./assets/images/Max_logo_2025 1.png";
import mailIcon from "./assets/images/mail.png";
import mainImage from "./assets/images/main.jpg";
import mainLogo from "./assets/images/main_logo.png";
import teamImg1 from "./assets/images/img1.png";
import teamImg2 from "./assets/images/img2.png";
import teamImg3 from "./assets/images/img3.png";
import teamImg4 from "./assets/images/img4.png";
import teamImg5 from "./assets/images/img5.png";
import kraskiLogo from "./assets/images/kraski.png";
import footerAddressIcon from "./assets/images/Frame (2).png";
import footerEmailIcon from "./assets/images/Frame (3).png";
import footerMaxIcon from "./assets/images/Max_logo_2025 1 (1).png";
import footerLkIcon from "./assets/images/lk.png";

const contactsMenuOpen = ref(false);
</script>
