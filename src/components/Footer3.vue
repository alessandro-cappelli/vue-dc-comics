<template>
    <section>
        <div class="container-footer3">
            <div class="container-column">
                <div class="container-prima-colonna">
                    <div>
                        <p>DC COMICS</p>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                    </div>

                    <div>
                        <p>SHOP</p>
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>
                    </div>
                </div>

                <div class="container-seconda-colonna">
                    <p>DC</p>
                    <ul>
                        <li><a href="#">Terms Of Use</a></li>
                        <li><a href="#">Privacy policy (New)</a></li>
                        <li><a href="#">Ad Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subcriptions</a></li>
                        <li><a href="#">Talent Workshop</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </div>

                <div class="container-terza-colonna">
                    <p>SITES</p>
                    <ul>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>
                </div>
            </div>

            <div class="container-img-logo">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Footer3'
}
</script>

<style scoped>
 .container-footer3{
     display: flex;
     background-image: url(../assets/img/footer-bg.jpg);
     color: white;
     background-repeat: no-repeat;
     background-size: cover;
     justify-content: space-between;
     height: 270px;
 }
.container-column{
    display: flex;
}
 .container-prima-colonna, .container-seconda-colonna,
 .container-terza-colonna{
     display: inline-block;
     margin-left: 5px;
 }

ul{
    list-style: none;
    padding: 0;
}
li{
    text-decoration: none;
}
li a {
    text-decoration: none;
    color: gray;
}

.container-img-logo{
    height: 100%;

}

img{
    height: 100%;
}
</style>

