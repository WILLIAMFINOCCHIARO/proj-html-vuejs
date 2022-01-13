<template>
  <nav>
    <div class="container pt-2">
      <div id="bar" class="row justify-content-between align-items-center">
        <div class="logo col-4">
          <img src="../assets/images/takeout-logo.png" class="img-fluid">
        </div>
        <div class="col-6 ">
            <ul class="nav nav-pills text-muted d-flex align-items-center ">
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#" role="button" aria-expanded="false">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link " aria-current="page" href="#">Order Online</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">About</a>
              </li>
              <li class="nav-item">
                <a class="nav-link">News</a>
              </li>
              <li class="nav-item">
                <a class="nav-link">Contact Us</a>
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