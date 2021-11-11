<template>
  <div class="create-adSpace">
    <CreateOrUpdate></CreateOrUpdate>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import CreateOrUpdate from './components/createOrUpdate.vue'
export default Vue.extend({
  name: 'creatAdSpcac',
  components: {
    CreateOrUpdate
  }
})
</script>

<style>
</style>
