<script>
export default {
    
}
</script>
<template>
    <div class="bg-jumbo d-flex justify-content-center align-items-center">
        <div class="container text-center">
            <div class="col-12">
                <h1 class="text-uppercase text-white fs-1">Building inspiring spaces</h1>
                <h4 class="fs-6 mt-2">We Build Inspiring Residential & Commercial Spaces</h4>
                <div class="d-flex justify-content-center mt-4">
                    <button class="px-4 text-uppercase btn-1 me-2" href="#">Explore recent work</button>
                    <button class="px-4 text-uppercase btn-2" href="#">Get a quote today</button>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../style/partials/vars" as *;

.bg-jumbo {
    background-image: url("../../../src/assets/img/home-slider-62528242.jpg");
    background-size: cover;
    height: 500px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.btn-1 {
    background-color: $light_black;
    color: $grey;
    
    &:hover {
        background-color: $yellow;
        color: $light_black;
    }
}

.btn-2 {
    background-color: $yellow;
    color: $light_black;
    
    &:hover {
        background-color: $light_black;
        color: $grey;
    }
}

h4{
    color: $yellow;
}

button {
    padding: 5px 35px;
    border: none;
    outline: none;
    cursor: pointer;
}
</style>