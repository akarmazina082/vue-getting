<template>
  <!-- <div class="tile is-ancestor">
    <div class="tile is-vertical is-8">
      <div class="tile">
        <div class="tile is-parent is-vertical">
          <article class="tile is-child notification is-primary">
            <p class="title">Vertical...</p>
            <p class="subtitle">Top tile</p>
          </article>
          <article class="tile is-child notification is-warning">
            <p class="title">...tiles</p>
            <p class="subtitle">Bottom tile</p>
          </article>
        </div>
        <div class="tile is-parent">
          <article class="tile is-child notification is-info">
            <p class="title">Middle tile</p>
            <p class="subtitle">With an image</p>
            <figure class="image is-4by3">
              <img src="https://bulma.io/images/placeholders/640x480.png">
            </figure>
          </article>
        </div>
      </div>
      <div class="tile is-parent">
        <article class="tile is-child notification is-danger">
          <p class="title">Wide tile</p>
          <p class="subtitle">Aligned with the right tile</p>
          <div class="content">
           Content 
          </div>
        </article>
      </div>
    </div>
    <div class="tile is-parent">
      <article class="tile is-child notification is-success">
        <div class="content">
          <p class="title">Tall tile</p>
          <p class="subtitle">With even more content</p>
          <div class="content">
             Content
          </div>
        </div>
      </article>
    </div>
  </div> -->
  <div class="page page-light">
        <div class="wrapper">
   <div class="main">
       <div class="sale">
           <p class="sale-description">Зимняя распродажа</p>
           <h1 class="sale-title">СКИДКИ ДО 90%</h1>
           <a class="btn" href="">СМОТРЕТЬ МОДЕЛИ</a>
       </div>
       <div class="main-item box">
           <div class="box-price">
               <strike class="box-price-old">9 900 ₽</strike>
               <p class="box-price-new">1 900 ₽</p>
           </div>
           <img class="box-image" src="img/shoes.png" alt="shoes">
       </div>
   </div>
    </div>
    </div>
</template>

<script>

export default {
  name: 'PromotionSection'
}

</script>

<style >
.main{
    display: flex;
    justify-content: space-between;
}
.sale{
    flex: 0 0 50%;
}
.sale-description{
    font-size: 30px;
    letter-spacing: -0.6px;
}
.sale-title{
    font-size: 55px;
    font-weight: 700;
    margin-top: 30px;
    margin-bottom: 60px;
}
.box{
    position: relative;
}
.box-price{
    position: absolute;
    right: 0;
    top: 35px;
    text-align: right;
}
.box-price-old{
    font-size: 24px;
    font-weight: 700;
    
}
.box-price-new{
    font-size: 42px;
    font-weight: 700;
    color: #D84033;
    margin-top: 17px;
}
</style>
