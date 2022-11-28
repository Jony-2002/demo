<template lang="">
  <div class="my-8">
    <p class="text-gray-400">{{ subtitle }}</p>
    <h3 class="text-4xl font-bold my-3">{{ title }}</h3>
    <a class="text-sky-500 font-semibold" href="#">{{ link }}</a>
  </div>
</template>
<script>
export default {
  name: "CardInfo",
  props: {
    subtitle: String,
    title: String,
    link: String,
  },
};
</script>
<style lang=""></style>
