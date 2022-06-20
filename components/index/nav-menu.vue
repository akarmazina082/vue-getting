<template>
  <div class="container mb-6">
    <nav class="navbar" role="navigation">
      <div class="navbar-brand">
        <img src="~/assets/img/logo.svg" alt="logo">
      </div>
    </nav>

    <div class="navbar-menu">
      <div class="navbar-start">
        <a href="" class="navbar-item">
          <NuxtLink to="/mans">Для мужчин</NuxtLink>
        </a>
        <a href="" class="navbar-item">
          <NuxtLink to="/mans">Для женщин</NuxtLink>
        </a>
        <a href="" class="navbar-item">
          <NuxtLink to="/mans">Для детей</NuxtLink>
        </a>
      </div>

      <div class="navbar-end">
        <li class="nav-item"><a class="nav-link" href="">Оплата</a></li>
        <li class="nav-item"><a class="nav-link" href="">Доставка</a></li>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'NavMenu'
}

</script>
