<script>
export default {
  name: 'header'
}
</script>

<template>
  <div class="root">
    <div class="logo">
      <img src="../assets/img/dc-logo.png" alt="logo">
    </div>
    <nav>
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
    </nav>
  </div>
</template>

<style scoped>
  .root{
    display: flex;
    justify-content: center;
    align-items: center;
    justify-content: space-between;
    height: 120px;
    margin-left: 16%;
    margin-right: 16%;
  }

img{
  width: 80px;
}

ul{
  display: flex;
}

li{
  text-transform: uppercase;
  list-style: none;
  margin: 10px;
  font-weight: bold;
}

li:hover{
  color: #0282F9;
  cursor: pointer;
}
</style>

