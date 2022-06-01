<template>
  <Sidebar />
  <Main />
</template>

<script>
import Sidebar from './components/Sidebar.vue'
import Main from './components/main.vue'

export default {
  name: 'App',
  components: {
    Sidebar,
    Main
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  display: flex;
}
</style>
