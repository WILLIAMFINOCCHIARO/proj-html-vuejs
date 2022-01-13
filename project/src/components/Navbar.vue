<template>
  <nav>
    <div class="container pt-2">
      <div id="bar" class="row justify-content-between align-items-center">
        <div class="logo col-4">
          <img src="../assets/images/takeout-logo.png" >
        </div>
        <div class="col-6 ">
            <ul class="nav nav-pills text-muted d-flex align-items-center ">
              <li class="nav-item" v-for="(items,index) in navLink" :key="index">
                <a class="nav-link">{{items}}</a>
              </li>
              <li class="nav-item">
                <a class="nav-link"> <i  class="fas fa-shopping-basket"></i></a>
              </li>
          </ul>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
    name: "NavBar",
    data(){
        return {
            navLink: [
                "Home",
                "Order Online",
                "About",
                "News",
                "Contact Us"
            ]
        }
    }
}

</script>

<style lang="scss">
@import "@/assets/global.scss";
    #bar {
      height: 70px;
      li {
        color:$white_bg;
      }
    }
    a:hover {
      color:$yellow_txt;
    }
    .col-6 {
      i   {
        font-size: 20px;
      }
    }

    
    
</style>