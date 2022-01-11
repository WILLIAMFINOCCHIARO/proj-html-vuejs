<template>
  <header>
  <NavBar/>
  </header>
</template>

<script>
import NavBar from "@/components/NavBar.vue"
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