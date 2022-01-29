<template>
    <div class="container">
        <section class="section-footer4">
            <div>
                <button>SIGN-UP NOW!</button>
            </div>

            <div class="container-icon">
                <ul>
                    <li><a href="#">FOLLOW US</a></li>
                    <li><a href="#"><img src="../assets/img/footer-facebook.png"></a></li>
                    <li><a href="#"><img src="../assets/img/footer-twitter.png"></a></li>
                    <li><a href="#"><img src="../assets/img/footer-youtube.png"></a></li>
                    <li><a href="#"><img src="../assets/img/footer-pinterest.png"></a></li>
                    <li><a href="#"><img src="../assets/img/footer-periscope.png"></a></li>
                </ul>
            </div>

        </section>
    </div>
</template>

<script>
export default {
    name: 'Footer4' 
}
</script>

<style scoped>
.section-footer4{
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 80px;
    background-color: #303030;
}

.container-icon{
    display: flex;
    
}
li{
    display: inline-block;
}

li a{
    text-decoration: none;
    color: gray;
}

</style>