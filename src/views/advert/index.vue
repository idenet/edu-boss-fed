<template>
  <div class="advert">
    <advertList></advertList>
  </div>
</template>
<script lang="ts">
import Vue from 'vue'
import advertList from './components/List.vue'
export default Vue.extend({
  name: 'advert',
  components: {
    advertList
  }
})
</script>
<style lang="scss" scoped>
</style>
