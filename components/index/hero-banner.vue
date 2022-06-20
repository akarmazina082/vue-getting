<template>
      <div class="page-light">
         <div class="wrapper">
    <header class="header">
       <nav>
           <ul class="nav">
               <li class="nav-item"><a class="nav-link" href="">Для мужчин</a></li>
               <li class="nav-item"><a class="nav-link" href="">Для женщин</a></li>
               <li class="nav-item"><a class="nav-link" href="">Для детей</a></li>
           </ul>
       </nav>
        <img src="img/logo.svg" alt="logo"> 
            <ul class="nav">
                <li class="nav-item"><a class="nav-link" href="">Оплата</a></li>
                <li class="nav-item"><a class="nav-link" href="">Доставка</a></li>
            </ul>
            
    <button class="cart">
        <span class="cart-count"></span>
    </button>
  </header>
         </div>
    </div>
</template>

<script>

export default {
  name: 'HeroBanner',
}

</script>

<style>

.wrapper{
    max-width: 1110px;
    margin: 0 auto;
    padding-left: 15px;
    padding-right: 15px;
}

.header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-bottom: 26px;
    padding-top: 46px;
    /* margin-bottom: 26px; */
}

.nav{
    display:flex;
    list-style: none;
    padding-left: 0;
}
.nav-item{
    margin-right: 52px;
}

.nav-link{
    color: #212121;
    text-decoration: none;
}

</style>
