<template>
  <div>
    <input type="date" v-model="data" />
    <componente-data :dataParam="data"></componente-data>
  </div>
</template>

<script>
import ComponenteData from "./components/ComponenteData.vue";

export default {
  data() {
    return {
      data: null,
    };
  },
  components:{ ComponenteData },
};
</script>

<style>
#ComponenteDataapp {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
