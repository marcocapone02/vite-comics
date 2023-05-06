
<script>
export default {
  name: 'main'
}
</script>

<template>
  <div class="content">
    <div class="text">
      <h1> &rarr; content goes here &larr; </h1>
    </div>
  </div>
</template>

<style scoped>
.content{
  display: flex;
  justify-content: left;
  align-items: center;
  width: 100%;
  height: 130px;
  background-color: black;
}

h1{
  color: white;
  font-size: 26px;
}

.text{
  margin-left: 16%;
  margin-right: 16%;
}
</style>