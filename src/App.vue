<script>

import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppFotter from "./components/AppFotter.vue";

export default {
  components: {
    AppHeader,
    AppMain,
    AppFotter,
  },

  data() {
    return {

    }
  },
}

</script>

<template>

  <AppHeader />
  <AppMain />
  <AppFooter />

</template>

<style scoped></style>
