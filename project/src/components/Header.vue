<template>
  <header>
    <div class="logo w-"></div>
    <div class="logotwo"></div>
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
      height:650px;
      background-image:url("../assets/images/demo-takeout.jpg");
      background-size:100% 100%;
    }
  
</style>