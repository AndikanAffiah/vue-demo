<template>
  <div id="app">
    <div class="d-flex">
      <SideBar/>
      <main class="w-100">
        <NavBar/>
        <Main v-if="true"/>
        <!-- <Main2 v-if="true"/> -->
      </main>
    </div>
  </div>
</template>

<script>
import SideBar from './components/sidebar/SideBar.vue'
import NavBar from './components/navbar/NavBar.vue'
import Main from './components/Main.vue'
import Main2 from './components/Main2.vue'

export default {
  name: 'App',
  components: {
    SideBar,
    NavBar,
    Main,
    Main2
  }
}
</script>

<style>
  @import "./assets/style.css" 
</style>


