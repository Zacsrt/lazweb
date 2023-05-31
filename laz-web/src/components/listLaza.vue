<template>
  <div>
  <div class="headerbox">
  <h2>สินค้าเพื่อคุณโดยเฉพาะ</h2>
</div>
  <div class="lazbox">
  <slotLaza v-for="item in goods" :key="item.id">
    <template v-slot:plate-header>
      <div class="image-box">
      <img :src="item.image" alt="Goods Image" />
    </div>
      <p>{{ item.name }}</p>
    </template>
    <template v-slot:plate-content>
      <p>{{ item.price }}</p>
      <p>{{ item.count }}</p>
      <p>{{ item.star }}</p>
    </template>
  </slotLaza>
</div>
</div>
</template>

<script>
import axios from "axios";
import slotLaza from './slotLaza.vue';
export default {
    name: "listLaza",
  components: {
    slotLaza,
  },
  data() {
    return {
      goods: [],
    };
  },
  async mounted() {
    let result = await axios.get("http://localhost:3000/photo");
    console.log(result);
    this.goods = result.data;
  },
}
</script>

<style>
.headerbox h2{
  text-align: left;
  padding-left: 90px;
}
.lazbox{
  width: 90%;
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  grid-gap: 10px;
  padding-left: 90px;
}
.image-box{
  text-align: center;
}
</style>