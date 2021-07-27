<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view/>
  {{ name }}
  <button type="button" class="btn btn-primary">Primary</button>
</template>

<script>
export default {
  data() {
    return {
      name: process.env.VUE_APP_NAME,
      // https://cli.vuejs.org/zh/guide/mode-and-env.html#%E6%A8%A1%E5%BC%8F
    };
  },
};
</script>

<style lang="scss">
// 因為沒有加上scoped，因此所有地方都可以使用到bootstrap的class
// 在App.vue裡面引入bootstrap套件
@import "bootstrap";
</style>
