<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <MyComponent msg='This is my component!'/>
    <Name name='Kusal'/>
    <AboutMe msg='I am super cool.' />
  </div>
</template>

<script>
import MyComponent from './components/MyComponent.vue'
import AboutMe from './components/AboutMe'
import Name from './components/Name';
export default {
  name: 'App',
  components: {
    MyComponent,
    AboutMe,
    Name
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
