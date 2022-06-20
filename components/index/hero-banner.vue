<template>
  <div class="container">
    <div class="columns">
      <div class="column">
        <div class="sale">
          <p class="sale-description">Зимняя распродажа</p>
          <h1 class="sale-title">СКИДКИ ДО 90%</h1>
          <a class="btn" href="">СМОТРЕТЬ МОДЕЛИ</a>
        </div>
      </div>
      <div class="column">
        <div class="main-item box">
          <div class="box-price">
            <strike class="box-price-old">9 900 ₽</strike>
            <p class="box-price-new">1 900 ₽</p>
          </div>
          <img src="~/assets/img/shoes.png" alt="shoes">
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'HeroBanner',
}

</script>
