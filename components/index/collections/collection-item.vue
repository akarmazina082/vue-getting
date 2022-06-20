<template>
  <div>
    <h3>{{ title }}</h3>
    <p>
      {{ description }}
    </p>
    <img :src="require(`~/assets/img/${imageName}`)" alt="">
  </div>
</template>

<script>

export default {
  props: {
    title: {
      type: String,
      required: true
    },
    description: {
      type: String,
      required: true
    },
    imageName: {
      type: String,
      required: true
    }
  },
}

</script>
