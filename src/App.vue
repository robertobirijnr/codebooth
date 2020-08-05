<template>
  <div>
  <navBar/>
  <router-view></router-view>
  </div>
</template>

<script>
import  navBar from '@/components/navBar.vue'
  export default {
    components:{
      navBar
    }
    
  }
</script>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;

}

body {
    font-family: 'Poppins', sans-serif;
    background: #dfded6
}
</style>
