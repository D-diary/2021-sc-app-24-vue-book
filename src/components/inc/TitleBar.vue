<template>
  <div class="title-bar">
    <b-jumbotron class="jumbotron">
      <template #header>Vue Library Management System</template>

      <template #lead>
        Vue.js / Vuex / Vue-router를 활용한 도서 관리 시스템
      </template>

      <hr class="my-4" />
      <p>
        It uses utility classes for typography and spacing to space content out
        within the larger container.
      </p>

      <b-button variant="primary" href="#">Do Something</b-button>
      <b-button variant="success" href="#">Do Something Else</b-button>
    </b-jumbotron>
  </div>
</template>

<script>
export default {
  name: "TitleBar",
};
</script>

<style lang="scss" scoped>
.title-bar {
  background-color: $grey-color;
  color: $light-color;
  padding: 2em 0;
  .jumbotron {
    width: 90%;
    margin: auto;
  }
}
</style>
