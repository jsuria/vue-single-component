<script>
import Vue from 'vue';
import VueSingleComponent from '@/vue-single-component.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    VueSingleComponent
  }
});
</script>

<template>
  <div id="app">
    <vue-single-component />
  </div>
</template>
