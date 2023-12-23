<template>
  <div id="app" class="small-container">
    <h1>Hello, welcome to my Digital Garden!</h1>

    <main-page/>
  </div>
</template>

<script>
import MainPage from './components/MainPage.vue'

export default {
  name: 'app',
  components: {
    MainPage,
  },
}
</script>

<style>
  button {
    background: #009435;
    border: 1px solid #009435;
  }

  .small-container {
    max-width: 680px;
  }
</style>
