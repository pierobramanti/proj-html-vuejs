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
                <h5 class="fs-6 mt-2 mb-4 lh-lg text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio distinctio reprehenderit quam iusto,<br>sint nulla omnis ex debitis nisi aspernatur possimus repellendus adipisci</h5>
            </div>
        </div>
    </div>
    <div class="container mb-4">
        <div class="row">
            <div class="col-12 d-flex gap-2">
                <div class="col-4 ">
                    <img src="../../assets/img/project2-featured-15013609-400x400.jpg" class="img-fluid " alt="project 1">
                </div>
                <div class="col-4 ">
                    <img src="../../assets/img/project1-featured-294276386-600x600.jpg" class="img-fluid " alt="project 2">
                </div>
                <div class="col-4 ">
                    <img src="../../assets/img/project3-featured-189023420-600x600.jpg" class="img-fluid " alt="project 3">
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
</style>
