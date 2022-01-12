<template>
  <header>
    <div class="logo w-"></div>
    <div class="logotwo"></div>
    <NavBar/>
    <Jumbo/>
  </header>
</template>

<script>
import NavBar from "../components/Navbar.vue";
import Jumbo from "../components/Jumbo.vue"
export default {
    name:"Header",
    components: {
        NavBar,
        Jumbo,
    },
    
}
</script>

<style lang="scss">
@import "@/assets/global.scss";
    header {
      width:100%;
      height:700px;
      background-image:url("../assets/images/demo-takeout.jpg");
      background-size:100% 100%;
    }
  
</style>