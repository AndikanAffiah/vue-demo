<template>
  <div id="app">
    <div class="d-flex">
      <SideBar/> 
      <Main/>
    </div>
  </div>
</template>

<script>
import SideBar from './components/SideBar.vue'
import Main from './components/Main.vue'

export default {
  name: 'App',
  components: {
    SideBar,
    Main
  }
}
</script>

<style>
  @import "./assets/style.css"
</style>


