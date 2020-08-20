<template>
    
</template>



<script>
import SideBar from './sidebar/SideBar.vue'
import NavBar from './navbar/NavBar.vue'

export default {
  name: 'Main',
  props: {
    msg: String
  },
  components: {
    SideBar,
	NavBar
  }
}
</script>