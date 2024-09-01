<script>
import { trusted } from '../data/components';
export default {
    data() {
        return {
            trusted
        }
    }
}
</script>


<template>
    <div class="container">
        <div class="row">
            <div class="col-12 text-center border">
                <h3 class=" fs-1 fw-lighter">Trusted Partners</h3>
                <hr class="fw-bolder">
                <h4 class="fonts-9 mt-2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio distinctio reprehenderit quam iusto, <br>sint nulla omnis ex debitis nisi aspernatur possimus repellendus adipisci aut, quod fugiat quisquam dolorem minus enim?</h4>
            </div>
            <div class="d-flex align-items-center justify-content-around mt-3">
                <div class="d-flex align-items-center">
                    <a class="img-fluid me-3">
                        <img src="../../assets/img/home-logo11-219096700-320x202.png" alt="home logo 1">
                    </a>
                    <a class="w_square me-3">
                        <img src="../../assets/img/home-logo2-219096700-320x202.png" alt="home logo 2">
                    </a>
                    <a class="w_square me-3">
                        <img src="../../assets/img/home-logo10-219096700-320x202.png" alt="home logo 1">
                    </a>
                    <a class="w_square me-3">
                        <img src="../../assets/img/home-logo1-219096700-320x202.png" alt="home logo 1">
                    </a>
                    <a class="w_square me-3">
                        <img src="../../assets/img/home-logo9-219096700-320x202.png" alt="home logo 1">
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
    border: solid 1px;
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