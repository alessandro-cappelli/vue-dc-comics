<template>
  <div class="container">
      <section class="section-header">
          <div>
              <img src="../assets/img/dc-logo.png" alt="">
          </div>

          <nav class="menu">
              <ul>
                  <li><a href="#">CHARACTERS</a></li>
                  <li><a href="#">COMICS</a></li>
                  <li><a href="#">MOVIES</a></li>
                  <li><a href="#">TV</a></li>
                  <li><a href="#">GAMES</a></li>
                  <li><a href="#">COLLECTIBLES</a></li>
                  <li><a href="#">VIDEOS</a></li>
                  <li><a href="#">FANS</a></li>
                  <li><a href="#">NEWS</a></li>
                  <li><a href="#">SHOP</a></li>
              </ul>
          </nav>

      </section>
  </div>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style>
.section-header{
    display: flex;
    align-items: center;
    justify-content: space-between;
    
}

/* lista menu */
.menu{
    display: flex;
}

li{
    display: inline-block;
    margin-left: 20px;
    margin-right: 20px;
}

li a{
    text-decoration: none;
    color: black;
}

</style>