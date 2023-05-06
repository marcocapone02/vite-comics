<script>
import card from './card.vue';
export default {
  name: 'main', 
  components: {
    card
  }
}

</script>

<template>
  <div class="img"></div>
  <div class="root">
    <card v-for="(serie, index) in series" :series="serie.series" :thumb="serie.thumb" :key="index" />
  </div>
</template>

<style scoped>

.img{
  height: 50vh;
  background-size: cover;
  background-image: url(../assets/img/jumbotron.jpg);
}
.root{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  background-color: ;
}
h1{
  color: white;
}
</style>