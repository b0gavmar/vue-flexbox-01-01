<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    
  </header>
  <div class="container">
    <div class="lila"></div>
    <div class="lila"></div>
    <div class="lila"></div>
    <div class="lila"></div>
  </div>
</template>

<style scoped>
.container{
  display: flex;
  flex-direction: row;
  background-color: yellow;
  height: 300px;
  justify-content: space-between;
  align-items: center;
}
.lila{
  width: 100px;
  height: 100px;
  background-color: purple;
  margin: 1px;
}

</style>
