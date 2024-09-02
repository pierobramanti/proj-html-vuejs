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
                <h5 class="fs-6 mt-2 mb-4 lh-lg text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio distinctio reprehenderit quam iusto,<br>sint nulla omnis ex debitis nisi aspernatur possimus repellendus adipisci</h5>
            </div>
            <div class="d-flex align-items-center justify-content-around mt-2 mb-4">
                <div class="d-flex align-items-center">
                    <a class="img-fluid me-3">
                        <img class="w-75" src="../../assets/img/home-logo11-219096700-320x202.png" alt="home logo 1">
                    </a>
                    <a class="w_square me-3">
                        <img class="w-75" src="../../assets/img/home-logo2-219096700-320x202.png" alt="home logo 2">
                    </a>
                    <a class="w_square me-3">
                        <img class="w-75" src="../../assets/img/home-logo10-219096700-320x202.png" alt="home logo 1">
                    </a>
                    <a class="w_square me-3">
                        <img class="w-75" src="../../assets/img/home-logo1-219096700-320x202.png" alt="home logo 1">
                    </a>
                    <a class="w_square me-3">
                        <img class="w-75" src="../../assets/img/home-logo9-219096700-320x202.png" alt="home logo 1">
                    </a>
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

div.d-flex {
    a {
        img {
            max-width: 100%;
            max-height: 100%;
            object-fit: contain;
            object-position: center
        }
    }

}

</style>