<template>
  <div class="container">
    <div class="columns">
      <div class="column">
        <collection-item
          :title="manCollections.title"
          :description="manCollections.description"
          :image-name="manCollections.imageSrc"
        />
      </div>
      <div class="column">
        <collection-item
          :title="womenCollection.title"
          :description="womenCollection.description"
          :image-name="womenCollection.imageSrc"
        />
      </div>
    </div>
  </div>
</template>

<script>

import CollectionItem from './collection-item';
export default {
  name: 'CollectionsSection',
  components: {CollectionItem},
  data() {
    return {
      manCollections: {
        title: 'Мужская коллекция TEST',
        description: 'Обувь, пуловеры',
        imageSrc: 'man.png'
      },
      womenCollection: {
        title: 'Женская коллекция TEST',
        description: 'Обувь, пуловеры',
        imageSrc: 'woman.png'
      }
    }
  },
}

</script>
