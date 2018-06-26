<template>
  <div id="app" class="container-fluid">
    <promotion v-for="promo in promos" v-bind:name="promo.name" v-bind:key="promo.id"></promotion>
  </div>
</template>

<script>
import Promotion from './components/Promotion.vue'
import PromotionsJSON from './data/promotions.json'

export default {
  name: 'app',
  components: {
    Promotion
  },
  data: function() {
    return {
      promos: PromotionsJSON.data.promotions
    }
  }
}
</script>
