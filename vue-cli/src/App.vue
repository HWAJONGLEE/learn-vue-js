<template>
  <div>
    <!-- <app-header v-bind:프롭스 속성 이름="상위컴포넌트 이름"></app-header> -->
    <app-header v-bind:propsdata="str"></app-header>
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
export default {
  data: function() {
    return {
      str: "Header"
    };
  },
  components: {
    "app-header": AppHeader
  }
};
</script>

<style>
</style>