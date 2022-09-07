<script>
export default {
  name: "Features"
}
</script>

<template>
  <div class="features">
    <div class="features-container">
      <div class="features-element">
        <img class="features-element-img"
             src="https://thumb.tildacdn.com/tild3466-6161-4234-a132-366433373461/-/resize/200x/-/format/webp/y1.png">
        <div class="features-element-title">ЛОКАЦИЯ</div>
        <div class="features-element-text">Удобные выезды на КАД,
          6-9 минут на транспорте до метро «Парнас», «Проспект Просвещения» и «Озерки»
        </div>
      </div>
      <div class="features-element">
        <img class="features-element-img"
             src="https://thumb.tildacdn.com/tild6166-6138-4365-a637-633064353036/-/resize/200x/-/format/webp/y3.png">
        <div class="features-element-title">НАДЕЖНОСТЬ</div>
        <div class="features-element-text">Застройщик работает по эскроу счетам и по 214 ФЗ «Об участии в долевом
          строительстве»
        </div>
      </div>
      <div class="features-element">
        <img class="features-element-img"
             src="https://thumb.tildacdn.com/tild3039-3436-4932-b431-316362633265/-/resize/200x/-/format/webp/y2.png">
        <div class="features-element-title">КВАРТАЛ</div>
        <div class="features-element-text">Невысокие дома<br>
          Панорамные виды на лес<br>
          Удобные планировки
        </div>
      </div>
    </div>
  </div>
</template>


<style scoped>
.features {
  display: flex;
  justify-content: center;
  /*border: 2px solid rosybrown;*/
}

.features-container {
  display: grid;
  grid-template-rows: 300px;
  grid-template-columns: 300px 300px 300px;
  grid-column-gap: 20px;
}

.features-element {
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  align-items: center;
}

.features-element-img {
  width: 30%;
}

.features-element-title {
  font: 28pt "Book Antiqua";
  color: dimgrey;
}

.features-element-text {
  font: 12pt "Book Antiqua";
  color: dimgrey;
  display: flex;
  text-align: center;
  height: 60px;
}
</style>