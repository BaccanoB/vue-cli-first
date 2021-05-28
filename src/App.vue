<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Title />
    <Hero />
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Hero from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    Title,
    Hero
  }
}
</script>

<style lang="scss">
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
#app {
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: cadetblue;
}
</style>
