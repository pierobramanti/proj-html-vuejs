<script>
export default {

}
</script>

<template>
    <div class="bg-carousel position-relative">
        <div class="container">
            <div class="row">
                <div class="col-12 d-flex flex-column justify-content-center align-items-center text-center h-100">
                    <h1 class="text-white fs-1 fw-lighter">Our Owners Says</h1>
                    <hr class="fw-bolder w-50">
                    <img src="../../assets/img/home-testimonial-113165296.jpg" alt="" class="my-3 rounded-circle">
                    <p class="text-white fw-medium lh-lg fst-italic">
                        "No man but feels more of a man in the world if he has but a bit of ground that he can call his own. However small it is on the surface, it is four thousand miles deep. And that is a very handsome property."
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../style/partials/vars" as *;

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
</style>
