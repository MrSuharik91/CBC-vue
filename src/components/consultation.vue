<template>
  <div class="consultation">
    <h1>Нужна консультация по выбору компьютерного оборудования?</h1>
    <h2>Остались вопросы? Задайте его в форме ниже:</h2>
    <div class="consultation-form-wrapper">
      <img src="/consultation.png" alt="" />
      <div class="inputs">
        <input
          class="first-input"
          type="text"
          v-model="name"
          placeholder="Имя"
        />
        <p class="hide-text" v-if="n">Имя должно начинатся с заглавной буквы</p>
        <input
          class="mid-input"
          v-model="number"
          type="number"
          placeholder="+7 --- --- -- --"
        />
        <p v-show="q">В тексте должны быть только цыфры</p>
        <input type="text" v-model="question" placeholder="Ваш вопрос" />
        <button @click="a" :style="{ opacity: g ? 1 : 0.5 }">
          Получить консультацию
        </button>
        <div class="chekbox-div">
          <input v-model="g" type="checkbox" />
          <p>
            Нажимая на кнопку я соглашаюсь
            <br />
            с политикой конфиденциальности
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
.consultation {
  width: 75%;
  margin: 0 auto;
  margin-top: 100px;
  text-align: center;
}
.consultation h1 {
  font-size: 30px;
  font-weight: 500;
  line-height: 40px;
}
.consultation h2 {
  margin-top: 15px;
  font-size: 22px;
  font-weight: 500;
  line-height: 29.28px;
}
.consultation-form-wrapper {
  box-shadow: 0px 0px 28px 0px #00000040;
  margin-top: 30px;
  display: flex;
  align-items: center;
  height: 546px;
}
.mid-input {
  margin-bottom: 32px;

  margin-top: 16px;
}
.consultation-form-wrapper input {
  border: 1px solid #4a4d4a;
  width: 250px;
  height: 60px;
}
.consultation-form-wrapper button {
  background: #ffaf37;
  width: 250px;
  height: 60px;
  margin-top: 32px;
  color: #ffffff;
  opacity: 0.5;
}
.chekbox-div {
  margin-top: 15px;
  display: flex;
  justify-content: center;
  gap: 10px;
}
.chekbox-div p {
  font-size: 10px;
  font-weight: 300;
  line-height: 14.93px;
  text-align: left;
}
.chekbox-div input {
  width: 30px;
  height: 30px;
}
input {
  padding-left: 15px;
}
.hide-text {
  font-size: 14px;
  color: red;
}
.first-input {
  margin-bottom: 16px;
}
input[type="number"]::-webkit-outer-spin-button,
input[type="number"]::-webkit-inner-spin-button {
  -webkit-appearance: none;
  margin: 0;
}
@media (max-width: 1400px) {
  .consultation-form-wrapper img {
    width: 60%;
  }
}
@media (max-width: 900px) {
  .consultation-form-wrapper img {
    width: 50%;
  }
  .consultation-form-wrapper input {
    width: 200px;
  }
  .consultation-form-wrapper button {
    width: 200px;
  }
  .chekbox-div input {
    width: 20px;
  }
}
@media (max-width: 600px) {
  .consultation-form-wrapper {
    display: flex;
    align-items: center;
    flex-direction: column;
  }
  .consultation-form-wrapper .inputs {
    display: flex;
    flex-direction: column;
  }
  .chekbox-div {
    display: flex;
  }
}
</style>
<script>
export default {
  data() {
    return {
      name: "",
      number: "",
      question: "",
      n: false,
      g: false,
    };
  },
  methods: {
    a() {
      if (this.name.charAt(0).toUpperCase() === this.name.charAt(0)) {
        this.name = "";
        this.number = "";
        this.question = "";
        this.n = false;
      } else {
        this.n = true;
        this.name = "";
        this.number = "";
        this.question = "";
      }
    },
  },
};
</script>
