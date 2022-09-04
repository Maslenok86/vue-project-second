<script>
export default {
  name: "Header",
};
</script>

<template>
  <div class="header">
    <div class="header-container">
      <div class="header-logos">
        <img
            src="https://thumb.tildacdn.com/tild3964-3431-4230-b561-336536616165/-/resize/169x/-/format/webp/logo_okla.png">
        <img src="https://thumb.tildacdn.com/tild6639-3035-4837-a661-393134623532/-/resize/122x/-/format/webp/_.png">
      </div>
      <div class="header-menu">
        <div class="header-menu-element">О квартале</div>
        <div class="header-menu-element">Квартиры</div>
        <div class="header-menu-element">Как купить</div>
        <div class="header-menu-element">Контакты</div>
      </div>
      <div class="header-phone">
        8 800 555 35 35
      </div>
      <div class="header-button-request">
        Заказать звонок
      </div>
    </div>

  </div>
</template>

<style scoped>
.header {
  display: flex;
  flex-direction: row;
  justify-content: center;
  height: 100px;
  /*border: 2px solid rosybrown;*/
  font: 14pt "Book Antiqua";
}

.header-container {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  /*border: 2px solid rosybrown;*/
  width: 1200px;
}

.header-logos {
  display: flex;
  flex-direction: row;
  align-self: center;
  align-items: center;
  width: 310px;
  justify-content: space-between;
  /*border: 2px solid rosybrown;*/
}

.header-menu {
  display: flex;
  flex-direction: row;
  align-self: center;
  /*border: 2px solid rosybrown;*/
}

.header-menu-element {
  margin: 0 10px 0 10px;
}

.header-phone {
  align-self: center;
  /*border: 2px solid rosybrown;*/
  font-weight: bold;
}

.header-button-request {
  display: flex;
  justify-content: center;
  align-items: center;
  align-self: center;
  border: 2px solid rosybrown;
  border-radius: 40px;
  height: 40px;
  width: 180px;
  background-color: antiquewhite;
}
</style>
