<script>
export default {

}
</script>

<template>
    <div class="container">
        <div class="row">
            <div class="col-12 text-center mb-4 mt-4">
                <h3 class="fs-1 fw-lighter">Latest News</h3>
                <hr class="fw-bolder mt-2 mb-4">
                <h4 class="fonts-10 mt-2 mb-4 lh-lg">Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio distinctio reprehenderit quam iusto,<br>sint nulla omnis ex debitis nisi aspernatur possimus repellendus adipisci</h4>
            </div>
            <div class="col-12 d-flex">
                <div class="custom-card">
                    <img src="../../assets/img/blog-post-134132600-1200x723.jpg" class="card-img" alt="...">
                    <div class="card-body">
                        <h4 class="card-title">Redeveloping Florida's Southern Cost</h4>
                        <p class="card-date">December 7th, 2015</p>
                        <hr class="card-separator">
                        <p class="card-text">Technology is here to stay, Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda harum deserunt magnam aliquam labore tempora eum expedita corrupti ea dolores? Porro voluptatum a dignissimos iste similique ducimus eaque error explicabo!</p>
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

.custom-card {
    width: 18rem;
    border: 1px solid #ddd;
    border-radius: 0;
    overflow: hidden;
    display: flex;
    flex-direction: column;
}

.card-img {
    width: 100%;
    height: auto;
}

.card-body {
    padding: 15px;
}

.card-title {
    font-size: 1.25rem;
    color: #6c757d;
    font-weight: 500;
    margin-bottom: 10px;
}

.card-date {
    font-size: 0.875rem;
    color: #6c757d;
    margin-bottom: 10px;
}

.card-separator {
    width: 90%;
    border: solid 1px #ccc;
    margin: 10px auto;
}

.card-text {
    font-size: 1rem;
    color: #333;
    text-align: left;
}
</style>
