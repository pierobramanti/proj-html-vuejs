<script>
export default {
    
}
</script>

<template>
    <div class="bg-grey">
        <div class="container">
            <div class="row">
                <div class="col-12 d-flex flex-column align-items-center text-center mt-4">
                    <h3 class="fs-3 fw-semibold mb-2">Our Core Values</h3>
                    <hr class="fw-bolder mb-3">
                    <h5 class="fs-6 mt-2 mb-4 lh-lg text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio distinctio reprehenderit quam iusto,<br>sint nulla omnis ex debitis nisi aspernatur possimus repellendus adipisci</h5>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="row">
                <div class="col-12 d-flex justify-content-between mt-4">
                    <div class="col-3 d-flex flex-column align-items-center text-center">
                        <div class="icon-circle bg-blue d-flex justify-content-center align-items-center mb-3">
                            <i class="fs-3 fa-solid fa-house text-white"></i>
                        </div>
                        <h4 class="fw-lighter text-grey fs-5">Great Services</h4>
                        <hr class="hr-custom fw-bolder mb-3">
                        <p class="text-secondary">Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit</p>
                    </div>
                    <div class="col-3 d-flex flex-column align-items-center text-center">
                        <div class="icon-circle bg-violet d-flex justify-content-center align-items-center mb-3">
                            <i class="fs-3 fa-solid fa-gear text-white"></i>
                        </div>
                        <h4 class="fw-lighter text-grey fs-5">Highest Standard</h4>
                        <hr class="hr-custom fw-bolder mb-3">
                        <p class="text-secondary">Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit</p>
                    </div>
                    <div class="col-3 d-flex flex-column align-items-center text-center">
                        <div class="icon-circle bg-terracotta d-flex justify-content-center align-items-center mb-3">
                            <i class="fs-3 fa-solid fa-users-line text-white"></i>
                        </div>
                        <h4 class="fw-lighter text-grey fs-5">Professional Team</h4>
                        <hr class="hr-custom fw-bolder mb-3">
                        <p class="text-secondary">Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit</p>
                    </div>
                    <div class="col-3 d-flex flex-column align-items-center text-center">
                        <div class="icon-circle bg-green d-flex justify-content-center align-items-center mb-3">
                            <i class="fs-3 fa-regular fa-lightbulb text-white"></i>
                        </div>
                        <h4 class="fw-lighter text-grey fs-5">Creative Solutions</h4>
                        <hr class="hr-custom fw-bolder mb-3">
                        <p class="text-secondary">Neque porro quisquam est qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit</p>
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

.hr-custom {
    width: 20px;
    border-color: $black;
}

.icon-circle {
    width: 70px;
    height: 70px;
    border-radius: 50%;
    transition: background-color 0.3s; 
    cursor: pointer; 
}

.icon-circle:hover {
    background-color: $yellow;
}

.bg-blue {
    background-color: $blue;
}

.bg-violet {
    background-color: $violet;
}

.bg-terracotta {
    background-color: $terracotta;
}

.bg-green {
    background-color: $green;
}

.text-white {
    color: $white;
}
</style>
