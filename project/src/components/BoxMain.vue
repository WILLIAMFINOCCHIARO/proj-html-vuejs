<template>
  <section>
    <div class="container mt-3">
      <div class="row">
        <div class="col-3 text-center"><i class="far fa-clock"></i> 24/7 DELIVERY</div>
        <div class="col-3 text-center"><i class="fas fa-hamburger"></i> OVER 100 DISHES</div>
        <div class="col-3 text-center"><i class="fas fa-mobile-alt"></i> IN APP ORDERING</div>
        <div class="col-3 text-center"><i class="fas fa-car"></i> FAST DELIVERY</div>
      </div>
      <div class="row text-center pt-5 mt-5 fs-1 fw-bold">
        <span>Our Most Popular Dishes</span>
      </div>
      <div class="row pt-5  justify-content-center">
        <div class="col-3">
          <div class="card" >
            <img src="../assets/images/skin-on-fries-210x300.jpg" class="card-img-top img-fluid">
            <div class="card-body">
              <p class="card-text fw-bold">Skin On Fries</p>
              <div>$3.00-$6.00</div>
            </div>
          </div>
        </div>

        <div class="col-3">
          <div class="card" >
            <img src="../assets/images/choco-cookie-frappe-210x300.jpg" class="card-img-top">
            <div class="card-body">
              <p class="card-text fw-bold">Choco Cookie Frappe</p>
              <div>$4.99</div>
            </div>
          </div>

        </div>

        <div class="col-3">
          <div class="card" >
            <img src="../assets/images/donut-burger-210x300.jpg" class="card-img-top">
            <div class="card-body">
              <p class="card-text fw-bold">The Donut Burger</p>
              <div>$6.99</div>
            </div>
          </div>

        </div>
        
      </div>
      <div class="text-center mt-5">  <a href="#" class="btn btn-primary border-0 fw-bold rounded-pill px-4 py-2">START YOUR ORDER <i class="fas fa-arrow-circle-right"></i> </a></div>
    
    </div>
    <div id="wave" class="row mt-5">
      
    </div>
  </section>
</template>

<script>

</script>

<style lang="scss">
@import "@/assets/global.scss";
    section {
      z-index: 99;
      .btn {
        background-color:$red_txt;
        }
    }
    #wave {
      height: 300px;
      background-image: url("../assets/images/first-order-background-scaled.jpg");
      background-size: 100% 100%;
    }
    .col-3 {
      .card-body{
        div {
      color:$red_txt;
      font-size: 15px;
      font-weight: bold;
      }
      p {
        font-size: 25px;
      }
    } 
    }
    
    
  
</style>