<script></script>
<template>
  <div class="customer">
    <div class="customer-inner">
      <div class="customer-wrapper-button">
        <h1>
          Работаем с государственными заказчиками
          <br />
          по требовательным ТЗ
        </h1>
        <button>
          УЗНАТЬ О РАБОТЕ С ТЕНДЕРАМИ <img src="/line.svg" alt="" />
        </button>
      </div>
      <div class="customer-wrapper-company">
        <div>
          <img src="/university.png" alt="" />
          <h2>
            «Авиационный техникум
            <br />
            имени Казакова»
          </h2>
        </div>
        <div>
          <img src="/mfti.png" alt="" />
          <h2>МФТИ</h2>
        </div>
        <div>
          <img src="/aturn.png" alt="" />
          <h2>
            МБУС Раменского городского
            <br />
            округа ФК «Сатурн».
          </h2>
        </div>
        <div class="item-4">
          <img src="/cagi.png" alt="" />
          <h2>ФГУП «Цаги»</h2>
        </div>
        <div>
          <img src="/lii.png" alt="" />
          <h2>
            АО «ЛИИ
            <br />
            им. Громова»
          </h2>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
.customer {
  margin-top: 100px;
  width: 100%;
  background: #f0f0ff;
  height: 400px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.customer-inner h1 {
  font-size: 24px;
  font-weight: 400;
  line-height: 32px;
}
.customer-wrapper-button {
  display: flex;
  justify-content: space-between;
}
.customer-inner {
  padding-top: 22px;
  margin: 0 auto;
  width: 75%;
}
.customer-inner button {
  border: 2px solid #ffaf37;
  width: 400px;
  height: 60px;
  font-size: 16px;
  font-weight: 500;
  line-height: 18px;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 15px;
}
.customer-inner button:hover {
  background-color: #ffaf37;
  color: white;
  transition: 0.3s;
}
.customer-wrapper-company {
  display: flex;
  justify-content: space-between;
  margin-top: 30px;
  align-items: center;
}
.customer-wrapper-company div {
  display: flex;
  justify-content: end;
  height: 160px;
  align-items: center;
  flex-direction: column;
  gap: 10px;
  text-align: center;
}
.customer-wrapper-company div h2 {
  font-size: 17px;
  font-weight: 400;
  white-space: nowrap;
  line-height: 20px;
}
.customer-wrapper-company img {
  width: 150px;
  height: 70px;
}
@media (max-width: 1100px) {
  .customer-inner h1 {
    font-size: 20px;
  }
  .customer-inner button {
    width: 300px;
    height: 50px;
    font-size: 14px;
  }
  .customer-inner button img {
    width: 30px;
  }
  .customer-wrapper-company div h2 {
    font-size: 14px;
  }
  .customer-inner {
    width: 90%;
  }
}
@media (max-width: 750px) {
  .customer-inner button img {
    width: 20px;
  }
  .customer-inner button {
    width: 280px;
    white-space: nowrap;
    font-size: 12px;
  }
  .customer-wrapper-company {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr;
    gap: 20px;
    margin: 0 auto;
  }
  .customer {
    height: 600px;
  }
}
@media (max-width: 600px) {
  .customer-inner button {
    width: 300px;
    white-space: nowrap;
    font-size: 9px;
  }
  @media (max-width: 600px) {
    .customer-wrapper-company {
      grid-template-columns: 1fr 1fr;
      grid-template-rows: 1fr 1fr 1fr;
    }
    .customer {
      height: 800px;
    }
  }
}
</style>
