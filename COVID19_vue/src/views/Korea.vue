<template>
  <v-container>
    <div>
      <korea-total></korea-total>
      <br>
      <korea-graph></korea-graph>
      <br>
      <korea-list></korea-list>
    </div>
  </v-container>
</template>
<script>
import KoreaTotal from '../components/korea/KoreaTotal.vue';
import KoreaGraph from '../components/korea/KoreaGraph.vue';
import KoreaList from '../components/korea/KoreaList.vue';
export default {
  components: {
    KoreaList,
    KoreaTotal,
    KoreaGraph,
  },
};
</script>
<style scoped></style>
