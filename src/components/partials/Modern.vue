<script>
export default {

}
</script>

<template>
    <div class="container">
        <div class="row">
            <div class="col-12 text-center mb-4 mt-4">
                <h3 class="fs-3 fw-semibold mb-2">Specialist in Modern Construction</h3>
                <hr class="fw-bolder mb-3">
                <h5 class="fs-6 mt-2 mb-4 lh-lg text-secondary">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio distinctio reprehenderit quam iusto,<br>sint
                    nulla omnis ex debitis nisi aspernatur possimus repellendus adipisci
                </h5>
            </div>
        </div>
    </div>
    <div class="container mb-4">
        <div class="row">
            <div class="col-12 d-flex">
                <div class="col-3 card-container me-4">
                    <div class="card px-4 py-2 d-flex flex-column align-items-center bg-grey">
                        <div class="circle-icon d-flex align-items-center justify-content-center rounded-circle border">
                            <i class="fa-regular fa-building fs-1 text-secondary icon"></i>
                        </div>
                        <h1 class="fw-semibold fs-3 text-secondary">Buildings</h1>
                        <p class="text-center lh-lg">Lorem ipsum dolor sit amet consectetur adipisicing elit. Et eos natus ex maiores.</p>
                    </div>
                    <div class="card overlay bg-yellow d-flex flex-column align-items-center justify-content-center">
                        <h1 class="fw-normal fs-5 text-secondary text-uppercase">Artfully Crafted</h1>
                        <p class="text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                        <button class="px-4 text-uppercase" href="#">Get Quote</button>
                    </div>
                </div>
                <div class="col-3 card-container me-4">
                    <div class="card px-4 py-2 d-flex flex-column align-items-center bg-grey">
                        <div class="circle-icon d-flex align-items-center justify-content-center rounded-circle border">
                            <i class="fa-solid fa-arrows-rotate fs-1 text-secondary icon"></i>
                        </div>
                        <h1 class="fw-semibold fs-3 text-secondary">Renovate</h1>
                        <p class="text-center lh-lg">Lorem ipsum dolor sit amet consectetur adipisicing elit. Et eos natus ex maiores.</p>
                    </div>
                    <div class="card overlay bg-yellow d-flex flex-column align-items-center justify-content-center">
                        <h1 class="fw-normal fs-5 text-secondary text-uppercase">Artfully Crafted</h1>
                        <p class="text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                        <button class="px-4 text-uppercase" href="#">Get Quote</button>
                    </div>
                </div>
                <div class="col-3 card-container me-4">
                    <div class="card px-4 py-2 d-flex flex-column align-items-center bg-grey">
                        <div class="circle-icon d-flex align-items-center justify-content-center rounded-circle border">
                            <i class="fa-solid fa-house fs-1 text-secondary icon"></i>
                        </div>
                        <h1 class="fw-semibold fs-3 text-secondary">Construct</h1>
                        <p class="text-center lh-lg">Lorem ipsum dolor sit amet consectetur adipisicing elit. Et eos natus ex maiores.</p>
                    </div>
                    <div class="card overlay bg-yellow d-flex flex-column align-items-center justify-content-center">
                        <h1 class="fw-normal fs-5 text-secondary text-uppercase">Artfully Crafted</h1>
                        <p class="text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                        <button class="px-4 text-uppercase" href="#">Get Quote</button>
                    </div>
                </div>
                <div class="col-3 card-container me-4">
                    <div class="card px-4 py-2 d-flex flex-column align-items-center bg-grey">
                        <div class="circle-icon d-flex align-items-center justify-content-center rounded-circle border">
                            <i class="fa-solid fa-truck-moving fs-1 text-secondary icon"></i>
                        </div>
                        <h1 class="fw-semibold fs-3 text-secondary">Deliver</h1>
                        <p class="text-center lh-lg">Lorem ipsum dolor sit amet consectetur adipisicing elit. Et eos natus ex maiores.</p>
                    </div>
                    <div class="card overlay bg-yellow d-flex flex-column align-items-center justify-content-center">
                        <h1 class="fw-normal fs-5 text-secondary text-uppercase">Artfully Crafted</h1>
                        <p class="text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                        <button class="px-4 text-uppercase" href="#">Get Quote</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../style/partials/vars" as *;

hr {
    color: $yellow;
    width: 160px;
    border: solid 2px;
    margin: 0 auto;
}

.circle-icon {
    width: 80px; 
    height: 80px;
    background-color: $grey; 
    border: 2px solid $grey; 
}

.card-container {
    position: relative;

    .card {
        transition: transform 0.1s ease-in-out;
    }

    .icon {
        transition: opacity 0.1s ease-in-out;
    }

    .overlay {
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
        padding: 1rem;
        text-align: center;
    }

    &:hover .overlay {
        opacity: 1;
    }

}

button {
    background-color: rgb(245, 225, 137);
    padding: 5px 40px;
    outline: none;
    border: none;

    &:hover {
        background-color: $light_black;
        color: $grey;
    }
}
</style>
