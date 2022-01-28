<template>
  <section>
      <div class="container-footer">
          <div class="card-link">
              <div>
                <img class="img-icon" src="../assets/img/buy-comics-digital-comics.png" alt="">
              </div>
              <p>DiGITAL COMICS</p>
          </div>

          <div class="card-link">
              <div>
                <img class="img-icon" src="../assets/img/buy-comics-merchandise.png" alt="">
              </div>
              <p>DC MERCHANDISE</p>
          </div>

          <div class="card-link">
              <div>
                <img class="img-icon" src="../assets/img/buy-comics-subscriptions.png" alt="">
              </div>
              <p>SUBSCRIPTION</p>
          </div>

          <div class="card-link">
              <div>
                <img class="img-icon" src="../assets/img/buy-comics-shop-locator.png" alt="">
              </div>
              <p>COMIC SHOP LOCATOR</p>
          </div>

          <div class="card-link">
              <div>
                <img class="img-icon" src="../assets/img/buy-dc-power-visa.svg" alt="">
              </div>
              <p>DC POWER VISA</p>
          </div>

          
      </div>
  </section>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style>
    .container-footer{
        background-color: #0282F9;
        display: flex;
        align-items: center;
        color: white;
        justify-content: space-between;
        height: 190px;
    }

    .card-link{
        display: flex;
        align-items: center;
        cursor: pointer;
    }

    .img-icon{
        height: 75px;
    }

    .card-link p {
        margin-left: 15px;
    }
</style>