<template>
  <div class="about">
    <h1 class="bg-primary">This is an about page</h1>
    <Card></Card>
  </div>
  <h1>about h1</h1>
</template>

<script>
import Card from '../components/Card.vue';

export default {
  components: {
    Card,
  },
};
</script>

<style scoped>
/* 如果加上scoped */
  h1{
    color: red;
  }
</style>
