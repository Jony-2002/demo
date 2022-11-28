<template lang="">
  <main class="px-16 py-7 flex items-start justify-evenly flex-wrap gap-5 relative bottom-14">
    <SmallCardVue />
    <BigCardVue />
  </main>
</template>
<script>
import SmallCardVue from "./SmallCard.vue";
import BigCardVue from "./BigCard.vue";
export default {
  components: {
    SmallCardVue,
    BigCardVue
  },
};
</script>
<style lang=""></style>
