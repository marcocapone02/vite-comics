<script>
export default {
  name: 'header'
}
</script>

<template>
  <div>
    <div class="logo"></div>
    <ul>
      <li>charaters</li>
      <li>comics</li>
      <li>movies</li>
      <li>tv</li>
      <li>games</li>
      <li>collectibles</li>
      <li>videos</li>
      <li>fans</li>
      <li>news</li>
      <li>shop</li>
    </ul>
  </div>
</template>

<style>
  .root{
    background-color: black;
    display: flex;
    justify-content: center;
    align-items: center;
    justify-content: space-between;
    margin-left: 15%;
    margin-right: 15%;
    margin-top: 30px;
  }

img{
  width: 54px;
}

ul{
  display: flex;
}

li{
  list-style: none;
  margin: 12px;
}

li:hover{
  color: red;
  cursor: pointer;
}

li:hover::after{
  content:'';
  width: 100%;
  display: block;
  height: 6px;
  background-color: red;
}
</style>