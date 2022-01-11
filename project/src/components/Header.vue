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
    
    
</style>