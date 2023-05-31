<template>
  <div class="grid">
    <div class="b1">
      <headLaz/>
    </div>
    <div class="b2">
      <tabLaz/>
    </div>

    <div class="b3">
      <dropMenu />
    </div>

    <div class="b4">
      <buttonLaz />
    </div>

    <div class="b5">
      <listLaza />
    </div>
  </div>
</template>

<script>
import buttonLaz from "./buttonLaz.vue";
import dropMenu from "./dropMenu.vue";
import listLaza from "./listLaza.vue";
import tabLaz from './tabLaz.vue';
import headLaz from './headLaz.vue';

export default {
  name: "lazMain",
  components: {
    dropMenu,
    listLaza,
    buttonLaz,
    tabLaz,
    headLaz
  },
};
</script>

<style scoped>
@import "./layout.css";
</style>