<template>
  <div id="app">
    <production-list-one></production-list-one>
    <production-list-two></production-list-two>
  </div>
</template>

<script>
import ProductionListOne from '@/components/ProductionListOne.vue';
import ProductionListTwo from '@/components/ProductionListTwo.vue';

export default {
  name: 'app',
  components: {
    'production-list-one': ProductionListOne,
    'production-list-two': ProductionListTwo
  },
  data() {
    return {
      
    }
  }
}
</script>

<style>
body {
  font-family: Ubuntu;
  color: #555;
}
</style>
