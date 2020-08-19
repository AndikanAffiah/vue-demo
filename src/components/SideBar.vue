<template>
  <aside class="position-relative expanded">
    <div class="logo p-3">
      <span class="sidebar-logo"></span>
    </div>

    <hr class="faded">
    
    <div class="side-nav py-3 d-flex justify-content-center flex-column">
      
      <div class="d-flex justify-content-center my-2">
        <a class="icon-container active">
          <span class="icon home-icon"></span>
        </a>
      </div>
      <div class="d-flex justify-content-center my-2">
        <a class="icon-container">
          <span class="icon link-icon"></span>
        </a>
      </div>
      <div class="d-flex justify-content-center my-2">
        <a class="icon-container">
          <span class="icon people-icon"></span>
        </a>
      </div>
      <div class="d-flex justify-content-center my-2">
        <a class="icon-container">
          <span class="icon tabs-icon"></span>
        </a>
      </div>

    </div>
    
    <hr class="faded">
    
    <div class="py-3 d-flex justify-content-center flex-column">
      <div class="d-flex justify-content-center my-2">
        <a class="text-center text-white">
          <span class="icon-small one">HE</span>
        </a>
      </div>
      <div class="d-flex justify-content-center my-2">
        <a class="text-center text-white">
          <span class="icon-small two">YU</span>
        </a>
      </div>
      <div class="d-flex justify-content-center my-2">
        <a class="text-center text-white">
          <span class="icon-small three">DE</span>
        </a>
      </div>
      <div class="d-flex justify-content-center my-2">
        <a class="text-center text-white">
          <span class="icon-small four">ME</span>
        </a>
      </div>
    </div>

    <hr class="faded">

    <div class="logout-container">
      <a class="text-center text-white d-flex justify-content-center logout">
        <span class="arrow-right-icon"></span>
      </a>
    </div>
	
  </aside>
</template>

<script>
export default {
  name: 'SideBar',
  props: {
    msg: String
  }
}
</script>
