<template>
  <div class="s">
    <advertspacelist></advertspacelist>
  </div>
</template>
<script lang='ts'>
import Vue from 'vue'
import advertspacelist from './components/List.vue'
export default Vue.extend({
  name: 'advertpce',
  components: {
    advertspacelist
  }
})
</script>
<style lang="scss" scoped>
</style>
