<template>
  <div class="container">
    <AppHomeVue />
  </div>
</template>

<script>
import AppHomeVue from "~/containers/AppHome.vue";

export default {
  name: "IndexPage",
  components: { AppHomeVue },
};
</script>
