<script setup>
import { RouterLink, RouterView } from 'vue-router'


</script>

<template>

  <header class="container-fluid">

  </header>

  <div class="container-xl">
    <div class="row">

      <aside class="col-2">
        <ul class="sidebar-content-scroll">
          <li><a>创建一个应用</a></li>
          <li><a>创建一个应用</a></li>
          <li><a>创建一个应用</a></li>
          <li><a>创建一个应用</a></li>        
          <li><a>创建一个应用測試用</a></li> 
        </ul>
      </aside>

      <main class="col-10">
        <div class="main"></div>

        <RouterView />

      </main>

    </div>
   


    
  </div>



</template>

<style lang="scss" scoped>

aside{
  height: 100vh;

}
.sidebar-content-scroll{
  height:100%;
  position: fixed;
  overflow-y: auto; /* 允許滾動 */
  overflow-x: hidden;
  >li{
    margin-right: 20px;
  }

}
.main{
  /* height: 200vh; */
}

</style>
