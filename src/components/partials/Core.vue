<script>
export default {
    
}
</script>

<template>
    <div class="bg-grey">
        <div class="container">
            <div class="row">
                <div class="col-12 d-flex flex-column align-items-center text-center mt-4">
                    <h3 class="fs-3 fw-lighter mb-2">Our Core Values</h3>
                    <hr class="fw-bolder mb-3">
                    <h5 class="fonts-10 mt-2 mb-4 lh-lg">Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio distinctio reprehenderit quam iusto,<br>sint nulla omnis ex debitis nisi aspernatur possimus repellendus adipisci</h5>
                </div>
            </div>
       </div>
       <div class="container">
        <div class="row">
            <div class="col-12 d-flex">
                <div class="col-3 flex-column align-items-center">
                    <i class="fa-solid fa-house"></i>
                    <hr class="fw-bolder mb-3">
                    <p>Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit</p>
                </div>
                <div class="col-3">
                    <i class="fa-solid fa-gear"></i>
                    <hr class="fw-bolder mb-3">
                    <p>Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit</p>
                </div>
                <div class="col-3">
                    <i class="fa-solid fa-users-line"></i>
                    <hr class="fw-bolder mb-3">
                    <p>Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit</p>
                </div>
                <div class="col-3">
                    <i class="fa-regular fa-lightbulb"></i>
                    <hr class="fw-bolder mb-3">
                    <p>Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit</p>
                </div>
            </div>
        </div>
       </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../style/partials/vars" as *;

.bg-grey {
    background-color: $grey;
}

hr {
    width: 150px;
    color: $yellow;
    border: solid 2px;
}
</style>
