<script>
export default {

}
</script>

<template>
    <div>
        <div class="container-full">
            <div class="row">
                <div class="col-12 d-flex px-4 py-4">
                    <div class="col-3 border bg-color">
                        <img src="../assets/img/footer-logo.png" alt="">
                        <p class="lh-lg"> We are specialist in the costruction of unique and exclusive properties. Our work inspires. We pride ourselves on delivering outstanding quality and design for leading clients across the world.</p>
                        <button class="px-4 text-uppercase" href="#">Learn more</button>
                    </div>
                    <div class="col-3 border">
                        <p>ciao</p>
                    </div>
                    <div class="col-3 border">
                        <p>ciao</p>
                    </div>
                    <div class="col-3 border">
                        <p>ciao</p>
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
}

a{
    color:$light_black;
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