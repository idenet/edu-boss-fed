<template>
  <div class="edit-advertspace">
    <CreateOrUpdate :id="id"></CreateOrUpdate>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import CreateOrUpdate from './components/createOrUpdate.vue'
export default Vue.extend({
  name: 'editAdvertSpace',
  components: {
    CreateOrUpdate
  },
  props: {
    id: {
      type: [Number, String],
      required: true
    }
  }
})
</script>

<style>
</style>
