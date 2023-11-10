<script>
import titleSide from "../components/titleSide.vue";
import contentSide from "../components/contentSide.vue";
export default {
  data() {
    return {};
  },
  components: { titleSide, contentSide },
};
</script>
<template>
  <div class="d-flex h-100">
    <titleSide class="titleSide"></titleSide>
    <contentSide class="contentSide flex-grow-1"></contentSide>
  </div>
</template>

<style lang="scss" scoped>
.titleSide {
  width: 40%;
}
</style>
