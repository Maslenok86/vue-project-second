<script>
export default {
  name: "Footer"
}
</script>

<template>
  <div class="footer">
    <div class="footer-container">
      <div class="footer-main-part">
        <div class="footer-main-part-logos">
          <img
              src="https://thumb.tildacdn.com/tild6635-3965-4964-b738-623264333339/-/resize/200x/-/format/webp/logo2.png">
          <img src="https://thumb.tildacdn.com/tild6665-3235-4233-b364-323433396462/-/resize/160x/-/format/webp/w.png">
        </div>
        <div class="footer-main-part-phone">В Санкт-Петербурге: <br> 8 800 555 35 35</div>
        <div class="footer-main-part-developer">
          ООО «Специализированный застройщик «ЛСТ Эксперт»<br>
          Проектная декларация располагается на сайте НАШ.ДОМ.РФ <br>
          Политика конфиденциальности
        </div>
      </div>
      <div class="footer-button-request">Заказать звонок</div>
    </div>
  </div>
</template>

<style scoped>
.footer {
  display: flex;
  justify-content: center;
  height: 230px;
  background-color: #57555a;
}

.footer-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  width: 1100px;
}

.footer-main-part {
  width: 500px;
}

.footer-main-part-logos {
  display: flex;
  justify-content: space-between;
  flex-direction: row;
  align-items: center;
  margin: 20px 0 20px;
}

.footer-main-part-phone {
  font: 14pt "Book Antiqua";
  color: white;
}

.footer-main-part-developer {
  font: 12pt "Book Antiqua";
  color: white;
  margin: 20px 0 20px;
}

.footer-button-request {
  display: flex;
  justify-content: center;
  align-items: center;
  border: 2px solid rosybrown;
  border-radius: 40px;
  height: 40px;
  width: 180px;
  background-color: white;
  margin: 40px;
}
</style>