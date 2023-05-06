<script>

export default {
  name:'Card',
  props:{
    thumb: String,
    series: String,
  },
}
</script>
<template>
      <div class="card">
        <img :src="thumb">
        <span>{{ series }}</span>
      </div>
</template>


<style lang="scss" scoped>
.container{
  padding: 0px 200px;
}

.card{
  display: flex;
  justify-content: center;
  align-items: center;
  background-color:black;
  width: calc(100% / 6);
  padding: 0 15px;
  border: 0px;
  margin-top: 30px;
img{
  display: flex;
  justify-content: center;
  width: 50%;
  height: 50%;
  margin-bottom: 30px;
  }
}

span{
  color: white;
}

</style>