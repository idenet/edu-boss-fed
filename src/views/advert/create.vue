<template>
  <div class="advert-create">
    <craeteOrUpdate></craeteOrUpdate>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import craeteOrUpdate from './components/CreateOrUpdate.vue'
export default Vue.extend({
  name: 'advertCreate',
  components: {
    craeteOrUpdate
  }
})
</script>

<style>
</style>
