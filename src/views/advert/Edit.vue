<template>
  <div class="create">
    <craeteOrUpdate :advert_Id="advertId"></craeteOrUpdate>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import craeteOrUpdate from './components/CreateOrUpdate.vue'
export default Vue.extend({
  name: 'edit',
  components: {
    craeteOrUpdate
  },
  props: {
    advertId: {
      type: [Number, String],
      required: true
    }
  }
})
</script>

<style>
</style>
