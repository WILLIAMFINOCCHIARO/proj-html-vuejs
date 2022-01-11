<template>
  <header>
  <NavBar/>
  </header>
</template>

<script>
import NavBar from "../components/Navbar.vue";
export default {
    name:"Header",
    components: {
        NavBar
    },
    
}
</script>

<style lang="scss">
@import "@/assets/global.scss";
    header {
      width:100%;
      min-width: 1080px;
      height:800px;
      background-image:url("../assets/images/demo-takeout.jpg");
      background-size:100% 100%;
    }
  
</style>