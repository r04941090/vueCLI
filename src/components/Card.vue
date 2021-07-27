<template>
    <div class="card" style="width: 18rem;">
        <div class="card-body">
            <h5 class="card-title">{{title}}</h5>
            <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
            <p class="card-text">Some quick example text
              to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="card-link">Card link</a>
            <a href="#" class="card-link">Another link</a>
        </div>
    </div>
    <h1>card h1</h1>
    <h3>scss test</h3>
    <h4>css outside</h4>
</template>

<script>
export default {
  data() {
    return {
      title: '這是一段標題',
    };
  },
};
</script>

<style scoped lang="scss">
  /* scoped限制範圍，lang代表裡面使用的格式，import一個scss檔案 */
  @import "../assets/scss/main.scss";
  h3 {
    margin: 40px 0 0;
    color: $mainColor;
  }
</style>

<style src="../assets/css/Cardtest.css"></style>
<!-- 可以用標籤形式引入多個 -->
