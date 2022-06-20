<template>
  <div>
    <div class="block">
      <hero-banner/>
    </div>

    <div class="block">
      <promotion-section/>
    </div>

    <div class="block">
      <models-section/>
    </div>

    <div class="block">
      <collections-section/>
    </div>
  </div>
</template>

<script>
import CollectionsSection from '../components/index/collections/collections-section';
import HeroBanner from '../components/index/hero-banner';
import ModelsSection from '../components/index/models-section';
import PromotionSection from '../components/index/promotion-section';


export default {
  name: 'IndexPage',
  components: {CollectionsSection, ModelsSection, PromotionSection, HeroBanner },
}
</script>
