<script>
export default {
  name: "Promotion"
}
</script>

<template>
  <div class="promotion">
    <div class="promotion-grid-container">
      <div class="promotion-grid-letter">Ж</div>
      <div class="promotion-grid-line-horizontal"></div>
      <div class="promotion-grid-letter">И</div>

      <div></div>
      <div class="promotion-grid-img">
        <img class="promotion-img"
             src="https://thumb.tildacdn.com/tild3735-3630-4830-b366-616433373762/-/format/webp/_1160x550__3_1.jpg">
      </div>
      <div class="promotion-grid-line-vertical"></div>

      <div class="promotion-grid-letter">И</div>
      <div class="promotion-grid-line-horizontal"></div>
      <div class="promotion-grid-letter">В</div>
    </div>
  </div>
</template>

<style scoped>
.promotion {
  display: flex;
  justify-content: center;
  /*border: 2px solid rosybrown;*/
  margin: 40px;
}

.promotion-grid-container {
  display: grid;
  justify-items: center;
  align-items: center;
  grid-template-rows: 50px 500px 50px;
  grid-template-columns: 50px 1000px 50px;
  /*border: 2px solid red;*/
  font: 30pt "Book Antiqua";
  font-weight: bold;

}

.promotion-grid-letter {
  /*border: 1px solid blue;*/
}

.promotion-grid-line-horizontal {
  border: 2px solid #faab15;
  height: 0;
  width: 996px;
}

.promotion-grid-line-vertical {
  border: 2px solid #faab15;
  height: 496px;
  width: 0;
}

.promotion-grid-img {
  display: flex;
  align-items: center;
  /*border: 1px solid blue;*/
}

.promotion-img {
  width: 100%;
}
</style>