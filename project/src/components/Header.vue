<template>
  <header>
    <div class="logo text-end text-light"><i class="fas fa-plus"></i></div>
    <NavBar/>
    <div class="demons d-flex justify-content-end ">
        <button class="btn border-0 btn-primary d-flex flex-column "><a href="#"></a><i class="fas fa-list-ul"></i>Demos</button>
    </div>
    <div class="onsale d-flex justify-content-end">
        <button class="btn border-0 btn-primary d-flex flex-column"><a href="#"></a><i>$39</i>On Sale</button>
    </div>
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
      height:700px;
      background-image:url("../assets/images/demo-takeout.jpg");
      background-size:100% 100%;
      position: relative;
      .logo>i {
        background-color:red ;
        font-size: 20px;
        border-radius: 100%;
        padding: 15px;
        margin: 10px;
      }
      .demons,
      .onsale {
        margin:20px;
      }
      div {
        color:white;
      }
    }
    

  
</style>