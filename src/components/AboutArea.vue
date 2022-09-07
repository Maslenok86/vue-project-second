<script>
export default {
  name: "AboutArea"
}
</script>

<template>
  <div class="about-area">
    <div class="about-area-title">
      <div class="about-area-title-line-horizontal"></div>
      <div class="about-area-title-text"> О ЖИЛОМ КВАРТАЛЕ</div>
      <div class="about-area-title-line-horizontal"></div>
    </div>
    <div class="about-area-container">
      <div class="about-area-img">
        <img
            src="https://thumb.tildacdn.com/tild6261-3162-4462-b565-643066366661/-/cover/660x378/center/center/-/format/webp/photo.jpg">
      </div>
      <div class="about-area-text">
        Вдохните воздух Новоорловского заказника, воздух сосен и берез. Позавтракайте в кругу семьи и отправляйтесь на
        прогулку – в лес, к озеру, в парк. Жителям квартала «Окла» такая жизнь доступна ежедневно, ведь ваш дом
        находится в Приморском районе, в самом сердце зеленого массива, среди 140 гектаров леса. <br><br>

        Комплекс состоит из семиэтажных корпусов и точечных высотных зданий. На первых этажах зданий будут располагаться
        магазины и сервисы. Квартал с трёх сторон окружен лесным массивом.<br><br>

        Благоприятная экологическая обстановка и продуманная современная инфраструктура позволяют жителям планировать
        здоровое будущее для всей семьи.
        <div class="about-area-text-links">
          <div class="about-area-text-links-elements">Безопасность</div>
          <div class="about-area-text-links-elements">Все для семьи</div>
          <div class="about-area-text-links-elements">Надежность</div>
        </div>
      </div>

    </div>
  </div>
</template>

<style scoped>
.about-area {
  display: flex;
  flex-direction: column;
  align-items: center;
  /*border: 2px solid rosybrown;*/
  margin: 40px;
}

.about-area-title {
  display: grid;
  grid-template-rows: 50px;
  grid-template-columns: 325px 450px 325px;
  align-items: center;
  justify-items: center;
  margin: 20px;
  font: 28pt "Book Antiqua";
  color: dimgrey;
}

.about-area-title-line-horizontal {
  display: flex;
  border: 2px solid #faab15;
  height: 0;
  width: 300px;
}

.about-area-container {
  display: flex;
  flex-direction: row;
  margin: 20px;
  width: 1100px;
  /*border: 2px solid rosybrown;*/
}

.about-area-text {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  margin-left: 40px;
  font: 12pt "Book Antiqua";
  color: dimgrey;
}

.about-area-text-links {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
</style>