<template lang="">
  <header
    class="flex items-start justify-between flex-wrap gap-5 bg-[#00ba4d] min-h-[200px] px-16 py-7">
    <LogoVue />
    <UserDetailsVue />
  </header>
</template>
<script>
import LogoVue from "./Logo.vue";
import UserDetailsVue from "./UserDetails.vue";
export default {
  name: "Header",
  components: {
    LogoVue,
    UserDetailsVue,
  },
};
</script>
<style lang=""></style>
