<script>
export default {
    
}
</script>
<template>
    <div class="bg-bottom d-flex justify-content-center align-items-center">
        <div class="container">
            <div class="row">
                <div class="col-12 d-flex">
                    <div class="col-8">
                        <h1 class="text-white fs-1 fw-lighter">Building inspiring spaces</h1>
                        <hr class="fw-bolder">
                        <h4 class="fs-5 mt-2 text-white fw-lighter"> Vivamus sed consectetuer tellus dolor sit amet, consectetur adipiscing <br> lorem elit sadip ipsum ficilis uns</h4>
                    </div>
                    <div class="col-4">
                        <div class="justify-content-center mt-4 text-center">
                            <button class="px-4 text-uppercase btn-2" href="#">Get a quote today</button>
                            <h4 class="fs-6 mt-2 text-white fw-lighter"> Only takes few seconds</h4>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="bg-bottom-2">
    </div>
    <div class="bg-grey">
    </div>
</template>

<style lang="scss" scoped>
@use "../style/partials/vars" as *;

.bg-bottom {
    background-image: url("../../../src/assets/img/about-call-to-action-57862405.jpg");
    background-size: cover;
    background-position: 0 380px;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.bg-bottom-2 {
    background-image: url("../../../src/assets/img/about-call-to-action-57862405.jpg");
    background-size: cover;
    background-position: 0 240px;
    height: 35px;
}

.bg-grey{
    height: 10px;
    background-color: $black;
}

.btn-2 {
    background-color: $yellow;
    color: $light_black;
    
    &:hover {
        background-color: $light_black;
        color: $grey;
    }
}

hr {
    color: $yellow;
    width: 160px;
    border: solid 1px;
}

button {
    padding: 5px 35px;
    border: none;
    outline: none;
    cursor: pointer;
}
</style>