<script>
export default {

}
</script>

<template>
    <div class="bg-carousel position-relative">
        <div class="container h-100 d-flex align-items-center justify-content-center">
            <div class="row min-vh-100 d-flex justify-content-center align-items-center">
                <div class="col-12 d-flex flex-column justify-content-center align-items-center text-center">
                    <h1 class="text-white fs-1 fw-lighter mb-2">Our Home Owners Says</h1>
                    <hr class="fw-bolder w-50 mb-4">
                    <img src="../../assets/img/home-testimonial-113165296.jpg" alt="" class="my-3 rounded-circle">
                    <div class="d-flex">
                        <a href=""><i class="fa-solid fa-circle text-white me-2"></i></a>
                        <a href=""><i class="fa-regular fa-circle text-white me-2"></i></a>
                    </div>
                    <p class="text-white fw-medium lh-lg fst-italic px-5">
                        "No man but feels more of a man in the world if he has but a bit of ground <br> that he can call his own. However small it is on the surface, it is four thousand <br> miles deep. And that is a very handsome property."
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../style/partials/vars" as *;

.color-yellow{
    color: $yellow;
}

.bg-carousel {
    background-image: url("../../assets/img/home-parallax-144609983.jpg");
    background-size: cover;
    height: 550px;
    background-position: center;
    position: relative;
    overflow: hidden;

    &:before,
    &:after {
        content: '';
        position: absolute;
        width: 100%;
        height: 50px;
        background: $grey; 
    }

    &:before {
        top: 0;
        transform: translateY(-10%);
        border-radius: 0 0 100% 100%; 
    }

    &:after {
        bottom: 0;
        transform: translateY(10%);
        border-radius: 100% 100% 0 0; 
    }
}

hr {
    width: 30px;
    color: $yellow;
    border: solid 2px;
}

</style>

