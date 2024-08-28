<template>
  <div class="repair-wrapper">
    <div class="repair">
      <div>
        <h1>
          Ремонт и обслуживание компьютерной
          <br />
          техники в сервис-центре СВС
        </h1>
        <p>
          Ремонтируем компьютеры, ноутбуки,
          <br />
          оргтехнику, серверное оборудование.
        </p>
        <button>
          ПОСМОТРЕТЬ УСЛУГИ СЕРВИС ЦЕНТРА
          <img src="/line.svg" class="button-arrow" alt="" />
        </button>
      </div>

      <img class="repair-img" src="/repair-img.svg" alt="" />
    </div>
  </div>
</template>
<style>
.repair-wrapper {
  height: 300px;
  background: #f0f0ff;
  margin-top: 100px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.repair-wrapper button {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
  width: 400px;
  height: 61px;
  border: 2px solid #ffaf37;
}
.repair-wrapper button:hover {
  background-color: #ffaf37;
  color: white;
  transition: 0.5s;
}
.repair-wrapper h1 {
  font-size: 20px;
  font-weight: 500;
  line-height: 30px;
}
.repair-wrapper p {
  font-size: 16px;
  font-weight: 400;
  line-height: 20px;
  margin-bottom: 20px;
  margin-top: 20px;
}
.repair {
  width: 75%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
@media (max-width: 1000px) {
  .repair-img {
    width: 40%;
  }
  .repair-wrapper button {
    width: 300px;
    font-size: 12px;
  }
  .repair-wrapper h1 {
    font-size: 18px;
  }
  .button-arrow {
    width: 30px;
  }
}
@media (max-width: 800px) {
  .repair-img {
    width: 40%;
  }
  .repair-wrapper button {
    width: 350px;
    font-size: 12px;
  }
  .repair-wrapper h1 {
    font-size: 16px;
  }
  .button-arrow {
    width: 30px;
  }
  .repair {
    width: 90%;
  }
}
@media (max-width: 650px) {
  .repair-wrapper p {
    font-size: 14px;
  }
  .repair-img {
    width: 35%;
  }
  .repair-wrapper button {
    width: 300px;
    font-size: 10px;
  }
  .repair-wrapper h1 {
    font-size: 14px;
  }
  .button-arrow {
    width: 25px;
  }
  .repair {
    width: 95%;
  }
}
@media (max-width: 500px) {
  .repair-wrapper p {
    font-size: 12px;
  }
  .repair-wrapper button {
    width: 250px;
    font-size: 10px;
  }
  .repair-wrapper h1 {
    font-size: 12px;
  }
  .button-arrow {
    width: 20px;
  }
}
</style>
