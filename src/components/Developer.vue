<script>
export default {
  name: "Developer"
}
</script>

<template>
  <div class="developer">
    <div class="developer-title">
      <div class="developer-title-line-horizontal"></div>
      <div class="developer-title-text"> ЗАСТРОЙЩИК</div>
      <div class="developer-title-line-horizontal"></div>
    </div>
    <div class="developer-main-part">
      <img class="developer-main-part-img"
           src="https://thumb.tildacdn.com/tild3461-6537-4465-a664-333332633236/-/resize/296x/-/format/webp/121.png">
      <div class="developer-main-part-info">
        <img class="developer-main-part-info-logo"
             src="https://static.tildacdn.com/tild3330-3931-4638-b531-616263306539/lst.svg">
        <div class="developer-main-part-info-text">
          Мы работаем на рынке Санкт-Петербурга и Ленинградской области 25 лет. Все эти годы мы создаем полноценные
          европейские кварталы, строим жилые дома повышенной комфортности, детские сады и школы, административные здания
          и торговые комплексы. Своим особым подходом к девелопменту мы заслужили доверие потребителя и именно этот
          подход позволяет нам испытывать гордость за свой продукт.
        </div>
      </div>

    </div>
  </div>


</template>

<style scoped>
.developer {
  display: flex;
  flex-direction: column;
  align-items: center;
  /*border: 2px solid rosybrown;*/
  margin: 40px;
}

.developer-title {
  display: grid;
  grid-template-rows: 50px;
  grid-template-columns: 400px 300px 400px;
  align-items: center;
  justify-items: center;
  margin: 20px;
  font: 28pt "Book Antiqua";
  color: dimgrey;
}

.developer-title-line-horizontal {
  display: flex;
  border: 2px solid #faab15;
  height: 0;
  width: 375px;
}

.developer-main-part {
  display: flex;
  flex-direction: row;
  width: 1100px;
}

.developer-main-part-info {
  display: flex;
  flex-direction: column;
  justify-content: end;
  margin-left: 60px;
}

.developer-main-part-info-logo {
  width: 35%;
  margin-bottom: 20px;
}

.developer-main-part-info-text {
  font: 12pt "Book Antiqua";
  color: dimgrey;
}
</style>