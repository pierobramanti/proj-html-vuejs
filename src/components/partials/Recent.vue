<script>
export default {

}
</script>

<template>
    <div class="container mb-4">
        <div class="row">
            <div class="col-12 d-flex flex-column align-items-center text-center mt-4">
                <h3 class="fs-3 fw-semibold mb-2">Explore Recent Work</h3>
                <hr class="fw-bolder mb-3">
                <h5 class="fs-6 mt-2 mb-4 lh-lg text-secondary">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio distinctio reprehenderit quam iusto,<br />sint
                    nulla omnis ex debitis nisi aspernatur possimus repellendus adipisci
                </h5>
            </div>
        </div>
    </div>
    <div class="container mb-4">
        <div class="row">
            <div class="col-12 d-flex gap-3">
                <div class="col-4 position-relative">
                    <img src="../../assets/img/project2-featured-15013609-600x600.jpg" class="img-fluid" alt="project 1">
                    <div class="hover-overlay d-flex flex-column align-items-center justify-content-center text-center">
                        <div class="icon-container d-flex gap-3 mb-3">
                            <div class="icon-circle d-flex align-items-center justify-content-center rounded-circle">
                                <a href=""><i class="fa-solid fa-link color-yellow"></i></a>
                            </div>
                            <div class="icon-circle d-flex align-items-center justify-content-center rounded-circle">
                                <a href=""><i class="fa-solid fa-magnifying-glass color-yellow"></i></a>
                            </div>
                        </div>
                        <h2 class="text-white fs-4">Florida Health facility</h2>
                        <p class="text-white fs-6">Commercial</p>
                    </div>
                </div>
                <div class="col-4">
                    <img src="../../assets/img/project1-featured-294276386-600x600.jpg" class="img-fluid" alt="project 2">
                </div>
                <div class="col-4">
                    <img src="../../assets/img/project3-featured-189023420-600x600.jpg" class="img-fluid" alt="project 3">
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../style/partials/vars" as *;

hr {
    width: 150px;
    color: $yellow;
    border: solid 2px;
}

.hover-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: $yellow;
    opacity: 0;
    transition: opacity 0.3s ease-in-out;
    z-index: 10;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.col-4:hover .hover-overlay {
    opacity: 1;
}

.icon-circle {
    width: 50px;
    height: 50px;
    background-color: $white;
    border: 2px solid $white;
    display: flex;
    align-items: center;
    justify-content: center;
}

.text-white {
    color: $white;
}
</style>
