<template>
  <div>
    <header>
      <nav-menu/>
    </header>

    <div class="block">
      <Nuxt/>
    </div>

    <div class="footer">
      <div class="container">
        Footer
      </div>
    </div>
  </div>
</template>

<script>
import NavMenu from '../components/index/nav-menu';

export default {
  name: 'DefaultLayout',
  components: {NavMenu},
}
</script>
