<template>
  <section>
    <div class="container pt-3">
      <div class="row">
        <div class="col-3">24/7 DELIVERY</div>
        <div class="col-3">OVER 100 DISHES</div>
        <div class="col-3">IN APP ORDERING</div>
        <div class="col-3">FAST DELIVERY</div>
      </div>
      <div class="row text-center pt-3">
        <span>Our Most Popular Dishes</span>
      </div>
      <div class="row pt-5  justify-content-center">
        <div class="col-3">
          <div class="card" >
            <img src="../assets/images/skin-on-fries-210x300.jpg" class="card-img-top img-fluid">
            <div class="card-body">
              <p class="card-text">Skin On Fries</p>
              <div class="fs-5">$3.00-$6.00</div>
            </div>
          </div>
        </div>

        <div class="col-3">
          <div class="card" >
            <img src="../assets/images/choco-cookie-frappe-210x300.jpg" class="card-img-top">
            <div class="card-body">
              <p class="card-text">Choco Cookie Frappe</p>
              <div class="fs-5">$4.99</div>
            </div>
          </div>

        </div>

        <div class="col-3">
          <div class="card" >
            <img src="../assets/images/donut-burger-210x300.jpg" class="card-img-top">
            <div class="card-body">
              <p class="card-text">The Donut Burger</p>
              <div class="fs-5">$6.99</div>
            </div>
          </div>

        </div>
        
      </div>
      <div class="text-center mt-5">  <a href="#" class="btn btn-primary bg-dark rounded-pill px-4 py-2">START YOUR ORDER </a></div>
    
    </div>
    <div id="wave" class="row mt-5">
      
    </div>
  </section>
</template>

<script>

</script>

<style lang="scss">
@import "@/assets/global.scss";
    #wave {
      height: 300px;
      background-image: url("../assets/images/first-order-background-scaled.jpg");
      background-size: 100% 100%;
    }
  
</style>