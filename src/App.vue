<template>
  <div id="app">
    <img class="logo" alt="chaser" src="./assets/logo.png">
    <MainPage>
      Формирование анкеты кандидата
    </MainPage>
  </div>
</template>

<script>
import MainPage from './components/MainPage.vue'


export default {
  name: 'App',
  components: {
    MainPage
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
    .logo {
        position: absolute;
        top: 10px;
        right: 10px;
        width: 200px;
    }
</style>
