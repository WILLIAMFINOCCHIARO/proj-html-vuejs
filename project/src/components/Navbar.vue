<template>
  <nav>
    <div class="container pt-5">
      <div id="bar" class="row justify-content-between align-items-center">
        <div class="logo col-4">
          <img src="../assets/images/takeout-logo.png" class="img-fluid">
        </div>
        <div class="col-4">
            <ul class="nav nav-pills ">
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#" role="button" aria-expanded="false">Dropdown</a>
              </li>
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Active</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link">Disabled</a>
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
      background-color: red;
      li {
        color:$white_bg;
      }
    }
    a:hover {
      color:$yellow_txt;
    }
    
</style>