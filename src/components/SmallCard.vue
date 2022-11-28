<template lang="">
  <div class="shadow-md w-[500px] max-w-[100%] rounded-xl px-6 bg-white">
    <CardInfoVue
      subtitle="Текущий баланс"
      title="12,00 TJS"
      link="+ Пополнить" />
  </div>
</template>
<script>
import CardInfoVue from "./CardInfo.vue";
export default {
  name: "SmallCard",
  components: {
    CardInfoVue,
  },
};
</script>
<style lang=""></style>
