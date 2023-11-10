<script>
import AppMain from "./pages/AppMain.vue";
export default {
  data() {
    return {
      title: "ciao",
    };
  },
  components: { AppMain },
};
</script>
<template>
  <main>
    <AppMain></AppMain>
  </main>
</template>

<style lang="scss">
main {
  height: 100vh;
  background-color: #a1ffe0;
}
</style>
