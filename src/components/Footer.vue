<script>
export default {

}
</script>

<template>
    <div>
        <div class="container-full">
            <div class="row">
                <div class="col-12 d-flex px-4 py-4">
                    <div class="learn-more col-3 border bg-color">
                        <img src="../assets/img/footer-logo.png" alt="">
                        <p class="lh-lg"> We are specialist in the costruction of unique and exclusive properties. Our work inspires. We pride ourselves on delivering outstanding quality and design for leading clients across the world.</p>
                        <button class="px-4 text-uppercase" href="#">Learn more</button>
                    </div>
                    <div class="col-3 tweets border">
                        <h4>Latest tweets</h4>
                        <div class="col-12 d-flex">
                            <div class="col-2">
                                <img class="img-fluid" src="../assets/img/3a74ce3d0532b7773b174c45ca3bd05a_normal.png" alt="">
                            </div>
                            <div class="col-10">
                               <div class="d-flex justify-content-between">
                                <h4 class="fw-bold fs-6">ThemeFusion</h4>
                                <a class="mx-2" href="#"><i class="fa-brands fa-twitter"></i></a>
                               </div>
                               <div>
                                <h6>@Theme_Fusion</h6>
                                <p class="fonts-9 lh-sm fw-bolder "> Do you need sublime WordPress hosting for your next website? Take advantage of exclusive parteners offers that we have secured just for you, & launch your site in seconds with <a href=""> #avada</a> on WP Engine hosting & get 30% Off this Black Friday <a href=""> bit.ly/3kjLLE2 #BlackFriday2020</a></p>
                               </div>
                               <img class="img-fluid" src="../assets/img/En2TRxLW4AEiWUN.jpeg" alt="WP Engigneer">
                               <div class="d-flex justify-content-between">
                                <div>
                                    <a class="mx-2" href="#"><i class="fa-regular fa-heart"></i></a>
                                    <a class="mx-2" href="#"><i class="fa-solid fa-arrow-right-from-bracket"></i></a>
                                </div>
                                <p>22h</p>
                               </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-3 border">
                        <h4>Contact us today</h4>
                        <div class="d-flex">
                            <i class="fa-solid fa-globe mx-2"></i>
                            <p class="fonts-10 fw-bolder lh-lg"> Corporate Location 1600 Amphitheatre Parkway London Wc1 1Ba</p>
                        </div>
                    </div>
                    <div class="col-3 border">
                        <h4>Find us</h4>
                    </div>
                </div>
                
            </div>
        </div>
        <div class="container-full">
            <div class="row border">
                <div class="col-12 px-4">
                    <div class="py-4 d-flex justify-content-between">
                        <div>
                            <h5 class="text-uppercase">copy-right 2012-2015 avada theme by theme fusion | all right reserved | powered by wordpress</h5>
                        </div>
                        <div class="d-flex">
                            <a class="mx-2" href="#"><i class="fa-brands fa-facebook-f"></i></a>
                            <a class="mx-2" href="#"><i class="fa-brands fa-twitter"></i></a>
                            <a class="mx-2" href="#"><i class="fa-brands fa-youtube"></i></a>
                            <a class="mx-2" href="#"><i class="fa-brands fa-instagram"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../components/style/partials/vars" as *;

.container-full:nth-child(2) {
    background-color: $black;
}

.bg-color{
    background-color: $black;
}

h5 {
    font-size: 10px;
    color: $light_black;
}

p{
    color: $light_black; 
    a{
        color: blue;
    }
}

a{
   i{
    color:$light_black;
   }
}

button {
    background-color: $yellow;
    padding: 5px 40px;
    border: none;
    outline: none;

    &:hover {
        background-color: $light_black;
        color: $grey;
    }
}

</style>