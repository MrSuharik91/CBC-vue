<template>
  <div class="trust-wrapper">
    <h1>
      Нам доверяют поставлять, оптимизировать
      <br />
      и модернизировать компьютерную технику
    </h1>
    <div>
      <img class="dog" src="/dog.png" alt="" />
      <img class="monro" src="/monro.png" alt="" />
      <img class="mchs" src="/mchs.png" alt="" />
      <img class="alrosa" src="/alrosa.png" alt="" />
      <img class="dry" src="/dry.png" alt="" />
    </div>
  </div>
</template>
<style>
.trust-wrapper {
  width: 75%;
  margin: 0 auto;
  margin-top: 115px;
  background-image: url("/frame.png");
  background-size: contain;
  background-position: center;
  background-repeat: no-repeat;
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 42px 22px 40px 40px;
}
.trust-wrapper h1 {
  font-size: 22px;
  font-weight: 400;
  line-height: 30px;
}
.trust-wrapper div {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-top: 25px;
}
.dog {
  width: 140px;
  height: 140px;
}
.monro {
  width: 200px;
  height: 80px;
}
.mchs {
  width: 200px;
  height: 130px;
}
.alrosa {
  width: 200px;
  height: 133.33px;
}
.dry {
  width: 200px;
  height: 112.61px;
}
@media (max-width: 1300px) {
  .dog {
    width: 100px;
    height: 100px;
  }
  .monro {
    width: 150px;
    height: 60px;
  }
  .mchs {
    width: 150px;
    height: 100px;
  }
  .alrosa {
    width: 150px;
    height: 100px;
  }
  .dry {
    width: 150px;
    height: 100px;
  }
  .trust-wrapper h1 {
    font-size: 18px;
  }
  .trust-wrapper div {
    margin-top: 0px;
  }
}
@media (max-width: 1000px) {
  .trust-wrapper h1 {
    font-size: 16px;
    line-height: 20px;
  }
  .dog {
    width: 80px;
    height: 80px;
  }
  .monro {
    width: 100px;
    height: 50px;
  }
  .mchs {
    width: 100px;
    height: 80px;
  }
  .alrosa {
    width: 100px;
    height: 80px;
  }
  .dry {
    width: 100px;
    height: 80px;
  }
}
@media (max-width: 800px) {
  .trust-wrapper {
    width: 90%;
  }
  .trust-wrapper h1 {
    font-size: 16px;
    line-height: 20px;
  }
  .dog {
    width: 50px;
    height: 50px;
  }
  .monro {
    width: 80px;
    height: 40px;
  }
  .mchs {
    width: 80px;
    height: 70px;
  }
  .alrosa {
    width: 80px;
    height: 70px;
  }
  .dry {
    width: 80px;
    height: 70px;
  }
}
@media (max-width: 600px) {
  .trust-wrapper {
    width: 95%;
  }
  .trust-wrapper h1 {
    font-size: 15px;
    line-height: 20px;
  }
}
</style>
