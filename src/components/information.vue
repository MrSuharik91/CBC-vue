<script></script>
<template>
  <div class="grid-wrapper">
    <div class="gap span-1">
      Работать с СВС
      <br />
      выгодно
      <br />
      и надежно
    </div>
    <div class="gap">
      <img src="/reliable.svg" alt="" />
      <h1>Надежный поставщик</h1>
      <p>
        С 1993 года на рынке
        <br />
        Жуковского. 28 лет
        <br />
        рядом с вами.
      </p>
    </div>
    <div class="gap">
      <img src="/complex.svg" alt="" />
      <h1>Полный комплекс</h1>
      <p>
        Поставки, ремонт и
        <br />
        обслуживание в сервис- центре
        <br />
        СВС - все в одном месте
      </p>
    </div>
    <div class="gap">
      <img src="/key.svg" alt="" />
      <h1>Заказ под ключ</h1>
      <p>
        Подберем технику “под ключ”
        <br />
        по потребностям
        <br />
        и бюджету.
      </p>
    </div>
    <div class="gap span-2">
      <img src="/arrow-company.svg" alt="" />
      <h1>Прямые поставки</h1>
      <div class="company">
        <img src="/company.svg" alt="" />
        <img src="/company-2.svg" alt="" />
        <img src="/asus.svg" alt="" />
        <img src="/hp.svg" alt="" />
        <img src="/samsung.svg" alt="" />
        <img src="/intel.svg" alt="" />
        <img src="/lenovo.svg" alt="" />
      </div>
    </div>
    <div class="gap">
      <img src="/service.svg" alt="" />
      <h1>Надежный поставщик</h1>
      <p>
        С 1993 года на рынке
        <br />
        Жуковского. 28 лет
        <br />
        рядом с вами.
      </p>
    </div>
    <div class="gap">
      <img src="/cooperation.svg" alt="" />
      <h1>Надежный поставщик</h1>
      <p>
        С 1993 года на рынке
        <br />
        Жуковского. 28 лет
        <br />
        рядом с вами.
      </p>
    </div>
  </div>
</template>
<style>
.grid-wrapper {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-gap: 30px;
  margin: 0 auto;
  width: 75%;
  margin-top: 100px;
}
.gap {
  height: 250px;
  box-shadow: 0px 0px 11px 0px #00000040;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.gap:hover {
  background: #f0f0ff;
  transition: 0.3s;
}
.gap p {
  text-align: center;
}
.gap h1 {
  font-size: 20px;
  margin-top: 10px;
  margin-bottom: 10px;
  font-weight: 500;
  line-height: 30px;
}
.span-2 {
  grid-column: span 2;
}
.span-2 div {
  display: flex;
  align-items: center;
  gap: 25px;
}
.span-2 div img {
  width: 50px;
  height: 45px;
}
.span-2 h1 {
  margin-bottom: 25px;
}
.span-1 {
  background: #f0f0ff;
  font-size: 30px;
  font-weight: 500;
  line-height: 37.02px;
  text-align: center;
}
@media (max-width: 1200px) {
  .grid-wrapper {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr 1fr;
  }
}
@media (max-width: 650px) {
  .gap p {
    font-size: 12px;
  }
  .span-2 div img {
    width: 35px;
    height: 35px;
  }
  .gap h1 {
    font-size: 16px;
  }
  .span-1 {
    font-size: 24px;
  }
}
@media (max-width: 550px) {
  .span-2 div img {
    width: 30px;
    height: 30px;
  }
}
</style>
