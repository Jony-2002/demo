<template lang="">
  <div class="shadow-md w-[700px] max-w-[100%] rounded-xl px-6 bg-white">
    <CardInfoVue
      subtitle="Ваш тариф:"
      title="Биё! Фаъол бош - Сотрудник"
      link="Сменить тариф" />
    <CardInfoVue
      subtitle="Остатки минут по РТ:"
      title="102 минуты"
      link="Подключай минуты +" />
    <CardInfoVue
      subtitle="Остатки интернет трафика:"
      title="987 МБ"
      link="Подключай мегабайты +" />
    <CardInfoVue subtitle="Остатки бонусных баллов" title="150" link="Обменять" />
  </div>
</template>
<script>
import CardInfoVue from "./CardInfo.vue";

export default {
  name: "BigCard",
  components: {
    CardInfoVue,
  },
};
</script>
<style lang=""></style>
