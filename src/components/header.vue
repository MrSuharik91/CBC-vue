<script>
export default {
  data() {
    return {
      m: window.innerWidth < 950,
      k: false,
    };
  },
  methods: {
    c() {
      if (this.k === false) {
        this.k = true;
      } else {
        this.k = false;
      }
    },
    p() {
      if (this.k === true) {
        this.k = false;
      } else {
        alert("ajslk");
      }
    },
  },
};
</script>
<template>
  <header>
    <div v-if="k" class="header-button">
      <span @click="p" class="exit">
        <img src="/cross.png" alt="" />
      </span>
      <div>
        <h1>Сервисный центр</h1>
      </div>
      <div>
        <h1>Доставка и оплата</h1>
      </div>
      <div>
        <h1>Отзывы</h1>
      </div>
      <div>
        <h1>Личный кабинет</h1>
      </div>
      <div>
        <h1>О компании</h1>
      </div>
      <div>
        <h1>Контакты</h1>
      </div>
    </div>
    <div class="header-mini">
      <div class="header-inner">
        <img class="logo" src="/logo.svg" alt="" />
        <div class="big-div">
          <div class="link">
            <a href="">Сервисный центр</a>
            <a href="">Доставка и оплата</a>
            <a href="">Отзывы </a>
            <a href="">Личный кабинет</a>
            <a href="">О компании </a>
            <a href="">Контакты </a>
          </div>
          <button class="burger" v-if="m" @click="c">
            <img src="/burger.svg" alt="" />
          </button>
          <div class="contact">
            <p>
              СВС - надежный поставщик компьютерной
              <br />
              техники рядом с вами. 28 лет в Жуковском
            </p>
            <div class="btn-phone">
              <img src="/phone.jpg" alt="" />
              <h1>+7 495 723-09-69</h1>
              <button>заказать звонок</button>
            </div>
          </div>
        </div>
      </div>
      <div class="header-inner-2">
        <input type="text" placeholder="Поиск" />
        <div class="header-inner-3">
          <div class="wats-up">
            <img src="/telegram.svg" alt="" />
            <p>
              Напишите нам
              <br />
              в Whats APP
            </p>
          </div>
          <div class="mail">
            <img src="/mail.svg" alt="" />
            <p>mail@svs93.ru</p>
          </div>
          <div class="location">
            <img src="/location.svg" alt="" />
            <p>
              <span>г. Жуковский</span>
              <br />
              ул. Московская, 1
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="links-2">
      <div class="links-inner">
        <a href="">Комплексная поставка</a>
        <a href="">Пуско-наладка IT-оборудования</a>
        <a href="">Аудит и оптимизация парка печати</a>
        <a href="">Тендеры</a>
      </div>
    </div>
  </header>
</template>
<style scoped>
.header {
  width: 100%;
}
.header-inner-2 {
  display: flex;
  margin-top: 25px;
  justify-content: space-between;
}
input {
  border: 1px solid black;
  padding-left: 10px;
  height: 40px;
  width: 40%;
  font-size: 18px;
  margin-right: 80px;
}
.header-mini {
  width: 75%;
  margin: 0 auto;
  padding-top: 20px;
}
.header-inner {
  display: flex;
}
.contact {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.contact img {
  height: 30px;
  width: 30px;
}
.contact h1 {
  font-size: 22px;
  font-weight: 500;
  line-height: 20px;
}
.btn-phone {
  display: flex;
  align-items: center;
  gap: 10px;
}
.big-div {
  width: 80%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
.contact button {
  width: 200px;
  height: 37px;
  background: #ffaf37;
  font-size: 16px;
  font-weight: 500;
  line-height: 18px;
  color: white;
}
.link {
  font-size: 18px;
  line-height: 18px;
  display: flex;
  justify-content: space-between;
}
.contact p {
  font-size: 18px;
  font-weight: 400;
  line-height: 18px;
}
.logo {
  width: 20%;
  margin-right: 30px;
}
.wats-up {
  display: flex;
  font-size: 14px;
  gap: 10px;
  align-items: center;
}
.mail {
  display: flex;
  align-items: center;
  font-size: 14px;
  gap: 10px;
  font-weight: 500;
}
.location {
  display: flex;
  align-items: center;
  font-size: 14px;
  gap: 10px;
}
.header-inner-3 {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 60%;
}
.header-inner-3 span {
  font-weight: 600;
}
.links-inner {
  width: 75%;
  display: flex;
  justify-content: space-between;
  height: 60px;
  margin: 0 auto;
  align-items: center;
}
.links-2 {
  background: #f0f0ff;
  margin-top: 30px;
}
.burger img {
  width: 40px;
  height: 40px;
}
.burger {
  display: flex;
  justify-content: end;
  align-items: center;
}
.header-button {
  width: 100%;
  background-color: black;
  height: 100vh;
  gap: 20px;
  display: flex;
  flex-direction: column;
  position: fixed;
  align-items: center;
  padding-left: 40px;
  padding-right: 40px;
  padding-top: 40px;
  padding-bottom: 40px;
  z-index: 10;
}
.header-button div {
  width: 75%;
  border-radius: 15px;
  background: #151515;
  display: flex;
  justify-content: center;
  align-items: center;
  cursor: pointer;
  gap: 20px;
  height: 16vh;
}
.header-button div h1 {
  font-size: 16px;
  font-weight: 600;
  line-height: 16px;
  color: white;
}
.header-button div img {
  width: 30px;
  height: 30px;
}
.header-button div:hover {
  background-color: orange;
  transition: 1s;
}
.exit {
  width: 30px;
  height: 30px;
  background-color: white;
  position: absolute;
  right: 50px;
  cursor: pointer;
  top: 50px;
}
.exit:hover {
  background-color: rgb(93, 93, 93);
  transition: 0.5s;
}
@media (max-width: 1300px) {
  .contact p {
    font-size: 14px;
    font-weight: 400;
    line-height: 14px;
  }
  .link {
    font-size: 14px;
    line-height: 14px;
  }
  input {
    width: 30%;
    font-size: 16px;
    margin-right: 60px;
  }
  .contact h1 {
    font-size: 18px;
    font-weight: 500;
    line-height: 18px;
  }
  .contact img {
    height: 20px;
    width: 20px;
  }
}
@media (max-width: 1100px) {
  .links-inner a {
    font-size: 14px;
  }
  .contact p {
    display: none;
  }
  .link {
    font-size: 12px;
    line-height: 14px;
  }
  input {
    width: 25%;
    font-size: 16px;
    margin-right: 60px;
  }
  .contact h1 {
    font-size: 14px;
    font-weight: 500;
    line-height: 18px;
  }
  .contact img {
    height: 20px;
    width: 20px;
  }
  .header-inner-2 {
    justify-content: start;
  }
}
@media (max-width: 950px) {
  .links-inner a {
    font-size: 9px;
  }
  .link {
    display: none;
  }
  .btn-phone {
    display: none;
  }
  .wats-up {
    font-size: 12px;
    gap: 8px;
  }
  .mail {
    font-size: 12px;
    gap: 8px;
  }
  .location {
    font-size: 12px;
    gap: 8px;
  }
  .contact button {
    width: 150px;
    font-size: 14px;
    line-height: 16px;
  }
  .header-inner-3 {
    width: 80%;
  }
  .header-inner-3 img {
    width: 15px;
    height: 20px;
  }
  .header-inner-3 p {
    font-size: 10px;
  }
}
@media (max-width: 600px) {
  input {
    font-size: 14px;
    margin-right: 20px;
  }
  .header-inner-3 p {
    font-size: 9px;
  }
  .header-inner-3 img {
    width: 13px;
    height: 15px;
  }
}
</style>
