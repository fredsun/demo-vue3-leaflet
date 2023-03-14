<template>
  <MyMap mapkey="keyName" class="myMap" />
</template>

<script>
import MyMap from './components/my-map.vue';
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    MyMap
  }
}
</script>

<style scoped>
.myMap {
  /* width: 500px;
  height: 500px; */
  width: 100vw;
  height: 100vh;
}

body,
html {
  width: 100vw;
  height: 100vh;
}
</style>
