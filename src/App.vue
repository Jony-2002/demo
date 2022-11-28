<template lang="">
  <div class="min-h-[100vh] bg-[#ececec]">
    <HeaderVue />
    <MainVue />
  </div>
</template>
<script>
import HeaderVue from "./components/Header.vue";
import MainVue from "./components/Main.vue";
export default {
  components: {
    HeaderVue,
    MainVue,
  },
};
</script>
<style lang=""></style>
