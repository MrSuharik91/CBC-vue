<script></script>
<template>
  <footer>
    <div class="footer-wrapper">
      <div>
        <img class="logo" src="/logo.svg" alt="" />
        <h2>
          СВС - надежный
          <br />
          поставщик
          <br />
          компьютерной
          <br />
          техники рядом с вами
          <br />
          28 лет в Жуковском
        </h2>
      </div>
      <div>
        <h1>Популярные категории</h1>
        <p>
          Компьютерные поставки
          <br />
          и комплектующие
        </p>
        <p class="printer">Принтеры и МФУ</p>
        <p>Видеокарты</p>
        <p class="cartridges">Картриджи</p>
        <p>Акции</p>
      </div>
      <div>
        <h1>Услуги</h1>
        <p>
          Поставки картриджей
          <br />
          в офис
        </p>
        <p class="equipment">
          Пуско-наладка
          <br />
          оборудования
        </p>
        <p>
          Аудит парка
          <br />
          печатной техники
        </p>
      </div>
      <div>
        <h1>Информация</h1>
        <p class="delivery">Доставка и оплата</p>
        <p>Гарантии</p>
        <p class="comment">Отзывы</p>
        <p class="about">О компании СВС</p>
        <p>Политика конфиденциальности</p>
      </div>
      <div class="social-media">
        <img src="/instagram.svg" alt="" />
        <img class="facebook" src="/facebook.svg" alt="" />
        <img src="/watsup-2.svg" alt="" />
        <img class="wk" src="/wk.svg" alt="" />
        <img src="/person.svg" alt="" />
      </div>
      <div class="contact">
        <h1>Контакты</h1>
        <div class="first-footer-div">
          <img src="/phone-3.png" alt="" />
          <p>+7 495 723-09-69</p>
        </div>
        <div class="middle-footer-div">
          <img src="/mail.svg" alt="" />
          <p>Svs93@mail.ru</p>
        </div>
        <div>
          <img src="/location.svg" alt="" />
          <p><span>г. Жуковский</span> ул. Московская, 1</p>
        </div>
      </div>
    </div>
  </footer>
</template>
<style scoped>
footer {
  margin-top: 100px;
  background: #f0f0ff;
  width: 100%;
  height: 350px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.footer-wrapper {
  width: 75%;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr;
  justify-content: space-between;
}
.footer-wrapper div {
  text-align: center;
}
span {
  font-size: 18px;
  font-weight: 600;
  line-height: 29.86px;
  cursor: pointer;
}
.contact div {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
}
.middle-footer-div {
  margin-top: 23px;
  margin-bottom: 14px;
}
h1 {
  font-size: 18px;
  font-weight: 700;
  line-height: 21.33px;
  margin-bottom: 17px;
  cursor: pointer;
}
.facebook {
  margin-top: 18px;
  margin-bottom: 18px;
}
.wk {
  margin-top: 18px;
  margin-bottom: 18px;
}
.delivery {
  margin-top: 18px;
  margin-bottom: 18px;
}
.comment {
  margin-top: 18px;
  margin-bottom: 18px;
}
.about {
  margin-top: 18px;
  margin-bottom: 18px;
}
.equipment {
  margin-top: 18px;
  margin-bottom: 18px;
}
.printer {
  margin-top: 18px;
  margin-bottom: 18px;
}
.cartridges {
  margin-top: 18px;
  margin-bottom: 18px;
}
.logo {
  margin-bottom: 17px;
}
.social-media {
  display: grid;
  justify-content: center;
}
p {
  cursor: pointer;
}
.contact p {
  font-size: 14px;
  white-space: nowrap;
}
.contact span {
  font-size: 12px;
  font-weight: 500;
  line-height: 25px;
}
@media (max-width: 1400px) {
  .footer-wrapper {
    grid-template-columns: 1fr 1fr 1fr;
    grid-auto-rows: 1fr 1fr;
    row-gap: 50px;
  }
  footer {
    height: 700px;
  }
}
@media (max-width: 1000px) {
  .logo {
    width: 200px;
  }
  h1 {
    font-size: 16px;
    font-weight: 700;
    line-height: 19px;
  }
  p {
    font-size: 14px;
  }
}
@media (max-width: 900px) {
  .logo {
    width: 150px;
  }
  h1 {
    font-size: 14px;
    font-weight: 700;
    line-height: 17px;
  }
  p {
    font-size: 13px;
  }
}
@media (max-width: 750px) {
  .footer-wrapper {
    grid-template-columns: 1fr 1fr;
    grid-auto-rows: 1fr 1fr 1fr;
    row-gap: 50px;
  }
  footer {
    height: 1000px;
  }
}
</style>
