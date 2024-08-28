<script></script>
<template>
  <div class="grid">
    <div class="grid-inner bg">
      <img class="img-1" src="/offer2-icon-1.svg" alt="" />
      <img class="img-2" src="/offer2-icon-2.svg" alt="" />
      <div class="text-offer">
        <h1>
          Решаем cложные задачи интеграции
          <br />
          компьютерной техники
          <br />
          в ваш бизнес
        </h1>
        <p>
          Предоставим бесплатный тест
          <br />
          компьютерного оборудования
          <br />
          чтобы все работало как надо
        </p>
        <button>внедрить оборудование</button>
      </div>
    </div>

    <div class="grid-inner bg-1">
      <img class="img-1" src="/offer2-icon-3.svg" alt="" />
      <img class="img-2" src="/offer2-icon-4.svg" alt="" />
      <div class="text-offer">
        <h1>
          У вас много принтеров
          <br />
          и они часто ломаются
        </h1>
        <p>
          Проведем аудит печатной
          <br />
          техники и экономим
          <br />
          до 300 000 рублей в год
        </p>
        <button>УЗНАТЬ КАК</button>
      </div>
    </div>
  </div>
</template>
<style>
.grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-gap: 30px;
  justify-content: center;
  margin: 0 auto;
  width: 75%;
  margin-top: 130px;
}
.grid-inner {
  background: #e3e1ff;
  height: 400px;
  position: relative;
}
.bg {
  background: #f0f0ff;
}
.bg-1 {
  background: #e3e1ff;
}
.img-1 {
  position: absolute;
  top: 30px;
  left: 15px;
}
.img-2 {
  position: absolute;
  bottom: 0px;
  left: 0px;
  width: 220px;
}
.text-offer {
  height: 100%;
  display: flex;
  justify-content: center;
  flex-direction: column;
  position: absolute;
  right: 30px;
  direction: rtl;
}
.text-offer h1 {
  font-size: 20px;
  font-weight: 500;
  line-height: 24px;
  color: #4a4d4a;
}
.text-offer p {
  font-size: 16px;
  font-weight: 400;
  line-height: 20px;
  margin-bottom: 18px;
  margin-top: 18px;
  color: #4a4d4a;
}
.text-offer button {
  font-size: 14px;
  font-weight: 500;
  line-height: 18px;
  width: 180px;
  height: 50px;
  background: #ffaf37;
  color: #ffffff;
}
@media (max-width: 1200px) {
  .img-2 {
    width: 170px;
  }
  .text-offer button {
    width: 160px;
  }
}
@media (max-width: 1000px) {
  .grid-inner {
    height: 350px;
  }
  .img-2 {
    width: 140px;
  }
  .text-offer button {
    width: 140px;
  }
  .text-offer h1 {
    font-size: 14px;
  }
  .img-1 {
    width: 40px;
    height: 40px;
  }
  @media (max-width: 850px) {
    .grid-inner {
      height: 350px;
    }
    .img-2 {
      width: 200px;
    }
    .text-offer button {
      width: 200px;
    }
    .text-offer h1 {
      font-size: 18px;
    }
    .img-1 {
      width: 70px;
      height: 70px;
    }
    .grid {
      grid-template-columns: 1fr;
      grid-template-rows: 1fr 1fr;
    }
  }
}
@media (max-width: 600px) {
  .grid-inner {
    height: 350px;
  }
  .img-2 {
    width: 150px;
  }
  .text-offer button {
    width: 150px;
  }
  .text-offer h1 {
    font-size: 16px;
  }
  .img-1 {
    width: 50px;
    height: 50px;
  }
}
@media (max-width: 500px) {
  .img-1 {
    width: 40px;
    height: 40px;
  }
  .text-offer h1 {
    font-size: 14px;
  }
}
</style>
