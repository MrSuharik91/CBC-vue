<script></script>
<template>
  <div class="grid-category">
    <div class="top">
      <h1>
        Топ категорий
        <br />
        СВС
      </h1>
    </div>
    <div class="category">
      <img src="/ryzen.svg" alt="" class="img-category" />
      <div>
        <h1>Процессоры</h1>
        <img src="/line.svg" alt="" class="arrow" />
      </div>
    </div>
    <div class="category">
      <img src="/laptop.svg" alt="" class="img-category" />
      <div>
        <h1>Ноутбуки</h1>
        <img src="/line.svg" alt="" class="arrow" />
      </div>
    </div>
    <div class="category">
      <img src="/pc.svg" alt="" class="img-category" />
      <div>
        <h1>Системные блоки</h1>
        <img src="/line.svg" alt="" class="arrow" />
      </div>
    </div>

    <div class="category">
      <img src="/monitor.svg" alt="" class="img-category" />
      <div>
        <h1>Мониторы</h1>
        <img src="/line.svg" alt="" class="arrow" />
      </div>
    </div>
    <div class="category">
      <img src="/printer.svg" alt="" class="img-category" />
      <div>
        <h1>Принтеры</h1>
        <img src="/line.svg" alt="" class="arrow" />
      </div>
    </div>
    <div class="category">
      <img src="/mfu.svg" alt="" class="img-category" />
      <div>
        <h1>МФУ</h1>
        <img src="/line.svg" alt="" class="arrow" />
      </div>
    </div>
    <div class="category">
      <img class="card img-category" src="/graphics-card.svg" alt="" />
      <div>
        <h1>Видеокарты</h1>
        <img src="/line.svg" alt="" class="arrow" />
      </div>
    </div>
    <div class="category">
      <img src="/сartridges.svg" alt="" class="img-category" />
      <div>
        <h1>Картриджи</h1>
        <img src="/line.svg" alt="" class="arrow" />
      </div>
    </div>
    <div class="category">
      <img src="/microphone.svg" alt="" class="img-category" />
      <div>
        <h1>Микрофоны</h1>
        <img src="/line.svg" alt="" class="arrow" />
      </div>
    </div>
    <div class="category">
      <img src="/equipment.svg" alt="" class="img-category" />
      <div>
        <h1>Компьютерная техника</h1>
        <img src="/line.svg" alt="" class="arrow" />
      </div>
    </div>
    <div class="category-button">
      <button>ПОСМОТРЕТЬ ВСЕ КАТЕГОРИИ</button>
      <div>
        <h1></h1>
        <img src="/line.svg" alt="" class="arrow" />
      </div>
    </div>
  </div>
</template>
<style>
.grid-category {
  width: 75%;
  margin: 0 auto;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  gap: 25px;
  margin-top: 100px;
}
.grid-category .category {
  height: 250px;
  box-shadow: 0px 0px 19px 0px #00000040;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  padding-bottom: 33px;
  padding-top: 18px;
  cursor: pointer;
}
.grid-category .category div {
  width: 95%;
  margin-top: 22px;
  display: flex;
  justify-content: space-between;
  padding-left: 8px;
  padding-right: 15px;
}
.grid-category .category div h1 {
  font-size: 14px;
  font-weight: 500;
  white-space: nowrap;
  line-height: 20px;
}
.top {
  font-size: 30px;
  font-weight: 500;
  line-height: 30px;
  text-align: center;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #f0f0ff;
}
.category-button button {
  width: 85%;
  background: #ffaf37;
  height: 60px;
}
.category-button {
  height: 250px;
  box-shadow: 0px 0px 19px 0px #00000040;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding-bottom: 33px;
  padding-top: 18px;
  position: relative;
}
.category-button div {
  width: 95%;
  margin-top: 22px;
  display: flex;
  justify-content: end;
  padding-left: 8px;
  padding-right: 15px;
  position: absolute;
  bottom: 33px;
}
.card {
  height: 154px;
}
.category-button button {
  font-size: 12px;
  font-weight: 500;
  line-height: 17px;
  color: white;
}
@media (max-width: 1100px) {
  .grid-category .category div h1 {
    font-size: 10px;
  }
  .img-category {
    width: 80%;
  }
  .arrow {
    width: 25px;
  }
  .grid-category .category div h1 {
    font-size: 12px;
    white-space: wrap;
    line-height: 20px;
  }
  .grid-category {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
  }
}
@media (max-width: 850px) {
  .grid-category {
    font-size: 10px;
  }
  .grid-category {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;
  }
  .img-category {
    width: 60%;
  }
}
@media (max-width: 550px) {
  .grid-category {
    display: grid;
    grid-template-columns: 1fr;
    grid-template-rows: 1fr 1fr 1fr 1fr;
  }
  .img-category {
    width: 50%;
  }
}
</style>
