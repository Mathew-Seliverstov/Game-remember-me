<template>
  <div class="app">
    
    <img class="logo" alt="Vue logo" src="./assets/logo.png">

    <h1>Remember Me </h1>
    <p>Запомни и открой все зеленые клетки</p>

    <Board />
  </div>
</template>

<script>
import Board from './components/Board'

export default {
  name: 'App',
  components: {
    Board,
  }
}
</script>

<style scoped>
  .app {
    text-align: center;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    margin-top: 40px;

  }
  .logo {
    width: 100px;
  }
</style>
