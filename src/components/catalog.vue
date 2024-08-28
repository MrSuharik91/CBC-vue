<script>
export default {
  data() {
    return {
      pon: false,
    };
  },
  methods: {
    catal() {
      this.pon = !this.pon;
    },
  },

  mounted() {
    $(document).ready(() => {
      $(".slider").slick({
        dots: true,
        infinite: true,
        speed: 500,
        slidesToShow: 1,
        slidesToScroll: 1,
      });
    });
  },
};
</script>

<template>
  <div>
    <div class="catalog">
      <div class="catalog-inner">
        <div class="catalog-block">
          <div class="h1-catalog">
            <h1>Каталог</h1>
          </div>
          <div class="options" @click="catal">
            <span>
              <img src="/computer.svg" alt="" />
              <p>Компьютеры и комплектующие</p></span
            >
            <img src="/arrow.svg" alt="" />
          </div>
          <div class="options" @click="catal">
            <span>
              <img src="/accessory.svg" alt="" />
              <p>Периферия и аксессуары</p></span
            >
            <img src="/arrow.svg" alt="" />
          </div>
          <div class="options" @click="catal">
            <span>
              <img src="/foto.svg" alt="" />
              <p>Цифровое фото и видео</p></span
            >
            <img src="/arrow.svg" alt="" />
          </div>
          <div class="options" @click="catal">
            <span>
              <img src="/Networking.svg" alt="" />
              <p>Сетевое оборудование</p></span
            >
            <img src="/arrow.svg" alt="" />
          </div>
          <div class="options" @click="catal">
            <span>
              <img src="/materials.svg" alt="" class="phone" />
              <p>Расходные материалы</p></span
            >
            <img src="/arrow.svg" alt="" />
          </div>
          <div class="options" @click="catal">
            <span>
              <img src="/smartphone.svg" alt="" class="phone" />
              <p>Смартфоны, планшеты</p></span
            >
            <img src="/arrow.svg" alt="" />
          </div>
          <div class="options" @click="catal">
            <span>
              <img src="/tv.svg" alt="" />
              <p>Телевизоры, аудио-видео техника</p></span
            >
            <img src="/arrow.svg" alt="" />
          </div>
          <div class="options" @click="catal">
            <span>
              <img src="/computer.svg" alt="" />
              <p>Автомобильная техника</p></span
            >
            <img src="/arrow.svg" alt="" />
          </div>
          <div class="options" @click="catal">
            <span>
              <img src="/deffense.svg" alt="" />
              <p>Системы безопасности</p></span
            >
            <img src="/arrow.svg" alt="" />
          </div>
          <div class="options" @click="catal">
            <span>
              <img src="/sport.svg" alt="" />
              <p>Спорт, активный отдых</p></span
            >
            <img src="/arrow.svg" alt="" />
          </div>
          <div class="options" @click="catal">
            <span>
              <img src="/office.svg" alt="" />
              <p>Офисная техника</p></span
            >
            <img src="/arrow.svg" alt="" />
          </div>
          <div class="options" @click="catal">
            <span>
              <img src="/furniture.svg" alt="" />
              <p>Канцтовары и мебель</p></span
            >
            <img src="/arrow.svg" alt="" />
          </div>
          <div class="options" @click="catal">
            <span>
              <img src="/stock.svg" alt="" />
              <p>Акции</p></span
            >
            <img src="/arrow.svg" alt="" />
          </div>
          <div class="options" @click="catal">
            <span>
              <img src="/New.svg" alt="" />
              <p>Новинки</p></span
            >
            <img src="/arrow.svg" alt="" />
          </div>
        </div>
      </div>
      <div class="information-catalog">
        <h1>
          <span
            >Компьютерный магазин СВС в Жуковском Поставки компьютерной</span
          >
          техники, сервис-центр и услуги для компаний по IT-интеграции
        </h1>
        <div class="slider">
          <div id="slider-1">
            <div class="overlay">
              <h1>
                Ha работе очень много печатают
                <br />
                Приходится постоянно ремонтировать
                <br />
                МФУ и менять картриджи
              </h1>
              <p>
                Сократите расходы на обслуживание принтеров более чем на 50% за
                счет оптимизации печатного парка вашего офиса.
              </p>
              <button>получить бесплатный аудит</button>
            </div>
          </div>
          <div>
            <div class="overlay">
              <h1>
                Покупайте, ремонтируйте и обслуживайте
                <br />
                компьютерное оборудование в одном месте
                <br />
                -в центре СВС-Жуковский
              </h1>
              <p>
                Для этого вам совершенно не нужно ездить в Москву. Собственный
                <br />
                сервисный центр гарантирует качество, надежность и безопасность
                <br />
                ремонта за счет прямого контакта с производителями
              </p>
              <button>Заказать обслуживание</button>
            </div>
          </div>
          <div>
            <div class="overlay">
              <h1>
                Поставки компьютерной
                <br />
                техники для офисов
                <br />
                под “ключ”
              </h1>
              <button>СМОТРЕТЬ ПРЕДЛОЖЕНИЕ</button>
            </div>
          </div>
          <div>
            <div class="overlay">
              <h1>
                Оборудуем офис
                <br />
                “под ключ”
              </h1>
              <p>
                компьютерной техникой, периферией, мебелью
                <br />
                канцтоварами, а также вкусным кофе
              </p>
              <button>Укомплектовать офис под ключ</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
.catalog {
  padding-top: 50px;
  width: 75%;
  margin: 0 auto;
  display: flex;
  gap: 40px;
}
.catalog-block {
  width: 400px;
}
.slider {
  margin: auto;
  padding: 30px;
  width: 100%;
  max-width: 600px;
  box-sizing: border-box;
}
.h1-catalog {
  background: #f0f0ff;
  width: 100%;
  font-size: 18px;
  line-height: 29.28px;
  height: 40px;
  padding-left: 20px;
  display: flex;
  align-items: center;
}
.catalog-inner {
  box-shadow: 0px 4px 20px 0px #00000040;
  line-height: 300%;
  display: flex;
  height: 730px;
  position: relative;
  flex: 1;
}

.slick-next,
.slick-prev {
  background: grey;
  width: 30px;
  height: 30px;
}
.options span {
  display: flex;
  gap: 14px;
}
.options {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-left: 20px;
  padding-right: 15px;
  font-size: 16px;
  width: 400px;
}
.options:hover {
  cursor: pointer;
}

.information-catalog h1 span {
  font-size: 30px;
  font-weight: 500;
  line-height: 35px;
  color: #4a4d4a;
}
.information-catalog h1 {
  font-size: 25px;
  font-weight: 300;
  line-height: 30px;
  color: #4a4d4a;
}
.slick-next:focus,
.slick-next:hover,
.slick-prev:focus,
.slick-prev:hover {
  background: black;
}

#slick-slide00 {
  background-image: url(/slider-1.png);
  background-repeat: no-repeat;
  background-position: center;
  background-size: 100% 100%;
  height: 500px;
  width: 100%;
}
#slick-slide00 h1 {
  direction: rtl;
  font-size: 20px;
  font-weight: 500;
  color: rgb(255, 255, 255);
  line-height: 30px;
  margin-right: 20px;
  margin-bottom: 10px;
}
#slick-slide00 p {
  direction: rtl;
  font-size: 12px;
  font-weight: 500;
  line-height: 20px;
  color: rgb(255, 255, 255);
  margin-bottom: 10px;
  margin-right: 20px;
}
#slick-slide00 button {
  margin-right: 20px;
  width: 280px;
  height: 60px;
  background: #ffaf37;
  font-size: 16px;
  font-weight: 700;
  line-height: 20px;
  color: white;
}
#slick-slide01 {
  background-image: url(/slider-2.png);
  color: rgb(0, 0, 0);
  background-repeat: no-repeat;
  background-position: center;
  background-size: 100% 100%;
  height: 500px;
  display: flex;
  justify-content: center;
  align-items: end;
  flex-direction: column;
  width: 100%;
}
#slick-slide01 h1 {
  direction: rtl;
  font-size: 20px;
  font-weight: 500;
  color: rgb(255, 255, 255);
  line-height: 30px;
  margin-right: 20px;
  margin-bottom: 10px;
}
#slick-slide01 p {
  direction: rtl;
  font-size: 12px;
  font-weight: 500;
  line-height: 20px;
  color: rgb(255, 255, 255);
  margin-bottom: 10px;
  margin-right: 20px;
}
#slick-slide01 button {
  margin-right: 20px;
  width: 280px;
  height: 60px;
  background: #ffaf37;
  font-size: 16px;
  font-weight: 700;
  line-height: 20px;
  color: white;
}
#slick-slide02 {
  background-image: url(/slider-4.png);
  background-repeat: no-repeat;
  background-position: center;
  background-size: 100% 100%;
  height: 500px;
  width: 100%;
  position: relative;
}
#slick-slide02 h1 {
  text-align: center;
  font-size: 22px;
  line-height: 28px;
  color: white;
  margin-bottom: 10px;
  margin-right: 20px;
}
.overlay {
  display: flex;
  color: white;
  justify-content: center;
  align-items: end;
  flex-direction: column;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgb(88 88 88 / 21%);
  z-index: 1;
  width: 100%;
  height: 100%;
}
#slick-slide01 > div {
  position: relative;
  z-index: 2;
}
#slick-slide02 > div {
  position: relative;
  z-index: 2;
}
#slick-slide03 > div {
  position: relative;
  z-index: 2;
}
#slick-slide00 > div {
  position: relative;
  z-index: 2;
}
#slick-slide02 button {
  width: 280px;
  height: 60px;
  background: #ffaf37;
  font-size: 16px;
  font-weight: 700;
  line-height: 20px;
  margin-right: 20px;
  color: white;
}
#slick-slide03 {
  background-image: url(/slider-3.png);
  background-repeat: no-repeat;
  background-position: center;
  background-size: 100% 100%;
  height: 500px;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: end;
  flex-direction: column;
  color: white;
}
#slick-slide03 h1 {
  direction: rtl;
  font-size: 28px;
  font-weight: 500;
  line-height: 35px;
  margin-bottom: 10px;
  margin-right: 30px;
  color: white;
}
#slick-slide03 p {
  direction: rtl;
  font-size: 18px;
  font-weight: 500;
  margin-bottom: 10px;
  line-height: 20px;
  margin-right: 30px;
}
#slick-slide03 button {
  width: 300px;
  margin-right: 30px;
  height: 60px;
  background: #ffaf37;
  font-size: 16px;
  font-weight: 700;
  line-height: 20px;
  color: rgb(255, 255, 255);
  text-align: center;
}
@media (max-width: 950px) {
  .catalog {
    display: block;
  }
  .slider {
    width: 500px;
  }
  .catalog-inner {
    margin-bottom: 60px;
  }
  .catalog {
    width: 400px;
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .information-catalog h1 {
    font-size: 18px;
    line-height: 25px;
    font-weight: 400;
  }
  .information-catalog span {
    font-size: 20px;
    line-height: 25px;
    font-weight: 500;
  }
  #slick-slide00 h1 {
    font-size: 15px;
  }
  #slick-slide00 p {
    font-size: 10px;
  }
}
</style>
