<script>
export default {
  name: "Buying"
}
</script>

<template>
  <div class="buying">
    <div class="buying-title">
      <div class="buying-title-line-horizontal"></div>
      <div class="buying-title-text">КАК КУПИТЬ</div>
      <div class="buying-title-line-horizontal"></div>
    </div>
    <div class="buying-container">
      <div class="buying-option">
        <div class="buying-option-title">
          <div class="buying-option-title-white">ИПОТЕКА</div>
          <div class="buying-option-title-yellow">ОТ 0.1%</div>
        </div>
        <div class="buying-option-info">
          Планируете покупку квартиры в ипотеку? Специалисты Ленстройтреста помогут вам рассчитать наиболее подходящий
          вариант с комфортным ежемесячным платежом и оформят заявку.
          <div class="buying-option-info-button-more">ПОДРОБНЕЕ</div>
        </div>
      </div>
      <div class="buying-option">
        <div class="buying-option-title">
          <div class="buying-option-title-white">КВАРТИРА</div>
          <div class="buying-option-title-yellow">В ЗАЧЕТ</div>
        </div>
        <div class="buying-option-info">
          Хотите зафиксировать стоимость выбранной квартиры и отпраздновать новоселье до продажи прежней квартиры?
          Специалисты Ленстройтреста помогут подобрать варианты, оформят необходимые документы - за один визит.
          <div class="buying-option-info-button-more">ПОДРОБНЕЕ</div>
        </div>
      </div>
      <div class="buying-option">
        <div class="buying-option-title">
          <div class="buying-option-title-white">РАССРОЧКА</div>
          <div class="buying-option-title-yellow">НА 12 МЕСЯЦЕВ</div>
        </div>
        <div class="buying-option-info">
          Вы можете приобрести квартиру с помощью рассрочки платежей от застройщика на специальных условиях.
          <div class="buying-option-info-button-more">ПОДРОБНЕЕ</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.buying {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 40px;
}

.buying-title {
  display: grid;
  grid-template-rows: 50px;
  grid-template-columns: 400px 300px 400px;
  align-items: center;
  justify-items: center;
  margin: 20px;
  font: 28pt "Book Antiqua";
  color: dimgrey;
}

.buying-title-line-horizontal {
  display: flex;
  border: 2px solid #faab15;
  height: 0;
  width: 375px;
}

.buying-container {
  display: grid;
  grid-template-rows: 370px;
  grid-template-columns: 340px 340px 340px;
  grid-column-gap: 40px;
}

.buying-option {
  display: flex;
  flex-direction: column;
}

.buying-option-title {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background-color: #57555a;
  height: 260px;
}

.buying-option-title-white {
  font: 24pt "Book Antiqua";
  color: white;
}

.buying-option-title-yellow {
  font: 22pt "Book Antiqua";
  color: #faab15;
}

.buying-option-info {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  border: 2px solid #faab15;
  height: 100%;
  font: 12pt "Book Antiqua";
  color: dimgrey;
  padding: 20px;
}

.buying-option-info-button-more{
  display: flex;
  justify-content: center;
  align-items: center;
  height: 35px;
  width: 170px;
 background-color:  #faab15;
  border-radius: 40px;
  font: 14pt "Book Antiqua";
  color: dimgrey;
  font-weight: 800;
}
</style>