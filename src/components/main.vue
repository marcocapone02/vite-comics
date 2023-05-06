
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
  <div class="">
    <div class="img"></div>


    <div class="root">
      <card series="series"/>
      <card series="series"/>
      <card series="series"/>
      <card series="series"/>
      <card series="series"/>
      <card series="series"/>
      <card series="series"/>
      <card series="series"/>
      <card series="series"/>
    </div>
    
  </div>
</template>

<style scoped>

.img{
  background-size: cover;
  height: 40vh;
  background-image: url(../assets/img/jumbotron.jpg);
}
.root{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100px;
  background-color: black;
}
h1{
  color: white;
}
</style>