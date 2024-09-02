<script>
export default {

}
</script>

<template>
    <div class="container">
        <div class="row">
            <div class="col-12 text-center mb-4 mt-4">
                <h3 class="fs-3 fw-semibold mb-2">Trusted Partners</h3>
                <hr class="fw-bolder mb-3">
                <h5 class="fs-6 mt-2 mb-4 lh-lg text-secondary">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio distinctio reprehenderit quam iusto,<br>sint
                    nulla omnis ex debitis nisi aspernatur possimus repellendus adipisci
                </h5>
            </div>
        </div>
    </div>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="col-3 border p-3 d-flex flex-column align-items-center">
                    <div class="circle-icon d-flex align-items-center justify-content-center rounded-circle border">
                        <i class="fa-regular fa-building fs-1"></i>
                    </div>
                    <h1 class="">Buildings</h1>
                    <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Et eos natus ex maiores ut animi culpa repudiandae ab.</p>
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
    background-color: $white; 
    border: 2px solid $grey; 
}
</style>
