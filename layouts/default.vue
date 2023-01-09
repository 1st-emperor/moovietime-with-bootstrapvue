<template>
  <div>
    <AppHeader />

    <div style="background: #1e232b">
      <Nuxt />
    </div>

    <AppFooter />
  </div>
</template>

<script>
import AppHeader from "~/containers/AppHeader.vue";
import AppFooter from "~/containers/AppFooter.vue";

export default {
  name: "default",
  components: { AppHeader, AppFooter },
};
</script>
