<script></script>
<template>
  <div class="location-wrapper">
    <h1>
      Магазин компьютерной техники СВС
      <br />
      рядом с вами, в Жуковском
    </h1>
    <div class="location-inner">
      <div class="information-gap">
        <div class="information">
          <img src="/location.svg" alt="" />
          <h2>г. Жуковский, ул. Московская, д.1</h2>
        </div>
        <div class="information">
          <img src="/phone-2.svg" alt="" />
          <h2>+7 (495) 725-09-69</h2>
        </div>
        <div class="information">
          <img src="/mail.svg" alt="" />
          <h2>Svs93@mail.ru</h2>
        </div>
        <div class="information">
          <img src="/telegram.svg" alt="" />
          <h2>Напишите нам в Whats APP</h2>
        </div>
        <div class="information">
          <img src="/clock.svg" alt="" />
          <h2>Пн – Чт: с 9:00 до 19:00 Пт: с 9:00 до 17:00</h2>
        </div>
        <div class="information">
          <img src="/clock.svg" alt="" />
          <h2>Сб - Вс: принимаем онлайн-заказы</h2>
        </div>
      </div>
      <div>
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2254.175750310153!2d38.11081187664146!3d55.5989548730276!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x414abf4dc8426495%3A0x5fb47a27bc87833c!2z0JzQvtGB0LrQvtCy0YHQutCw0Y8g0YPQuy4sINCW0YPQutC-0LLRgdC60LjQuSwg0JzQvtGB0LrQvtCy0YHQutCw0Y8g0L7QsdC7Liwg0KDQvtGB0YHQuNGPLCAxNDAxODE!5e0!3m2!1sru!2sua!4v1724187441363!5m2!1sru!2sua"
          width="600"
          height="420"
          style="border: 0"
          allowfullscreen=""
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"
        ></iframe>
      </div>
    </div>
  </div>
</template>
<style>
.location-wrapper {
  width: 75%;
  margin: 0 auto;
  margin-top: 105px;
  box-shadow: 0px 0px 28px 0px #00000040;
  padding-top: 30px;
  padding-left: 7%;
  height: 600px;
  display: flex;
  justify-content: center;
  flex-direction: column;
}
.location-wrapper h1 {
  text-align: center;
  font-size: 26px;
  font-weight: 500;
  line-height: 37.02px;
  margin-bottom: 50px;
}
.information {
  display: flex;
  gap: 10px;
  align-items: center;
}
.information h2 {
  font-size: 17px;
  font-weight: 500;
  line-height: 20px;
}
.information img {
  width: 30px;
  height: 30px;
}
.location-inner {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.information-gap {
  display: flex;
  flex-direction: column;
  gap: 15px;
}
@media (max-width: 1300px) {
  iframe {
    width: 400px;
  }
  .information h2 {
    font-size: 15px;
  }
}
@media (max-width: 1300px) {
  iframe {
    width: 350px;
  }
  .information h2 {
    font-size: 13px;
  }
}
@media (max-width: 1000px) {
  .location-inner {
    display: flex;
    flex-direction: column;
    align-items: center;

    justify-content: center;
  }
  .location-wrapper {
    height: 900px;
    padding-left: 0px;
  }
  iframe {
    height: 350px;
    margin-top: 40px;
  }
}
@media (max-width: 600px) {
  .location-wrapper h1 {
    font-size: 16px;
  }
  iframe {
    width: 300px;
    height: 300px;
  }
}
</style>
