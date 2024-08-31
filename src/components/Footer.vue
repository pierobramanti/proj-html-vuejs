<script>
export default {

}
</script>

<template>
    <div class="footer bg-color-light-black">
        <div class="container">
            <div class="row">
                <div class="col-12 d-flex px-2 py-4">
                    <div class="learn-more col-3 me-2">
                        <img class="mb-4" src="../assets/img/footer-logo.png" alt="">
                        <p class="lh-lg fonts-11 text-secondary"> We are specialist in the costruction of unique and exclusive properties. Our work inspires. We pride ourselves on delivering outstanding quality and design for leading clients across the world.</p>
                        <button class="px-4 text-uppercase" href="#">Learn more</button>
                    </div>
                    <div class="col-3 tweets me-2">
                        <h6 class="mb-3 fw-bold">Latest Tweets</h6>
                        <div class="col-12 d-flex">
                            <div class="col-2">
                                <img class="img-fluid w-50 rounded-circle" src="../assets/img/3a74ce3d0532b7773b174c45ca3bd05a_normal.png" alt="">
                            </div>
                            <div class="col-10">
                               <div class="d-flex justify-content-between">
                                <h4 class="fw-bold fonts-10">ThemeFusion</h4>
                                <a class="mx-2" href="#"><i class="fa-brands fa-twitter"></i></a>
                               </div>
                               <div>
                                <p class="fw-light fonts-10 text-white ">@Theme_Fusion</p>
                                <p class="fonts-9 lh-sm fw-bolder text-white"> Do you need sublime WordPress hosting for your next website? Take advantage of exclusive parteners offers that we have secured just for you, & launch your site in seconds with <a href=""> #avada</a> on WP Engine hosting & get 30% Off this Black Friday <a href=""> bit.ly/3kjLLE2 #BlackFriday2020</a></p>
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
                    <div class="col-3 me-2">
                        <h6 class="mb-3 fw-bolder">Contact us today</h6>
                        <div class="d-flex">
                            <div>
                                <i class="fa-solid fa-globe mx-2 text-secondary"></i>
                            </div>
                            <div>
                                <p class="fonts-9 fw-bolder lh-lg text-secondary"> Corporate Location <br> 1600 Amphitheatre Parkway <br> London WC1 1Ba</p>
                            </div>
                        </div>
                        <div class="d-flex">
                            <div>
                                <i class="fa-solid fa-house mx-2 text-secondary"></i>
                            </div>
                            <div>
                                <p class="fonts-9 fw-bolder lh-lg text-secondary">Residential Location <br> 9521 broadsberry Avenue <br> Paddignton Rc7 gZA</p>
                            </div>
                        </div>
                        <div class="d-flex">
                            <div>
                                <i class="fa-solid fa-phone mx-2 text-secondary"></i>
                            </div>
                            <div>
                                <p class="fonts-9 fw-bolder lh-lg text-secondary"> 1.800.458.566 / 1800.532.2112</p>
                            </div>
                        </div>
                        <div class="d-flex">
                            <div>
                                <i class="fa-solid fa-envelope mx-2 text-secondary"></i>
                            </div>
                            <div>
                                <p class="fonts-9 fw-bolder lh-lg text-secondary">info@your-domani.com</p>
                            </div>
                        </div>
                        <div class="d-flex">
                            <div>
                                <i class="fa-regular fa-clock mx-2 text-secondary"></i>
                            </div>
                            <div>
                                <p class="fonts-9 fw-bolder lh-lg text-secondary"> Monday-Fryday 9:00 AM - 6:00 PM</p>
                            </div>
                        </div>
                        <div class="d-flex">
                            <div>
                                <i class="fa-regular fa-clock mx-2 text-secondary"></i>
                            </div>
                            <div>
                                <p class="fonts-9 fw-bolder lh-lg text-secondary"> Saturday - Sunday: 9:00 AM - 12:00 PM</p>
                            </div>
                        </div>   
                    </div>
                    <div class="col-3 me-2">
                        <h6 class="mb-3 fw-bolder">Find Us</h6>
                        <img class="img-fluid py-4" src="../assets/img/construction_map_pin.png-Notti" alt="">
                    </div>
                </div>
    
            </div>
        </div>
        <div class="bg-color-black">
            <div class="container">
                <div class="row">
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
    </div>
</template>

<style lang="scss" scoped>
@use "../components/style/partials/vars" as *;


.bg-color-black{
    background-color: $black;
}

.bg-color-light-black{
    background-color: $light_black;
}

.color-grey{
    color: $grey;
}

h5 {
    font-size: 10px;
    color: $light_black;
}

h6{
    color: $yellow;
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