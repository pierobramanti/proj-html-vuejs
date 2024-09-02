<script>
export default {

}
</script>

<template>
    <div class="bg-grey">
        <div class="container">
            <div class="row">
                <div class="col-12 text-center mb-4 mt-4">
                    <h3 class="fs-1 fw-lighter">Latest News</h3>
                    <hr class="fw-bolder mt-2 mb-4">
                    <h4 class="fs-6 mt-2 mb-4 lh-lg text-secondary">Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio distinctio reprehenderit quam iusto,<br>sint nulla omnis ex debitis nisi aspernatur possimus repellendus adipisci</h4>
                </div>
                <div class="col-12 d-flex justify-content-center gap-4">
                    <div class="custom-card">
                        <img src="../../assets/img/blog-post-134132600-1200x723.jpg" class="card-img" alt="...">
                        <div class="card-body bg-white">
                            <h4 class="card-title">Redeveloping Florida's Southern Cost</h4>
                            <p class="card-date">December 7th, 2015</p>
                            <hr class="card-separator">
                            <p class="card-text">Technology is here to stay, Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda harum deserunt magnam aliquam labore tempora eum expedita corrupti ea dolores? Porro voluptatum a dignissimos iste similique ducimus eaque error explicabo!</p>
                        </div>
                    </div>
                    <div class="custom-card">
                        <img src="../../assets/img/blog-post-92486644-1200x723.jpg" class="card-img" alt="...">
                        <div class="card-body bg-white">
                            <h4 class="card-title">How We manage Large construction Project</h4>
                            <p class="card-date">December 7th, 2015</p>
                            <hr class="card-separator">
                            <p class="card-text">Technology is here to stay, Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda harum deserunt magnam aliquam labore tempora eum expedita corrupti ea dolores? Porro voluptatum a dignissimos iste similique ducimus eaque error explicabo!</p>
                        </div>
                    </div>
                    <div class="custom-card">
                        <img src="../../assets/img/blog-post-332773904-1200x723.jpg" class="card-img" alt="...">
                        <div class="card-body bg-white">
                            <h4 class="card-title">Future Proving a modern Home</h4>
                            <p class="card-date">December 7th, 2015</p>
                            <hr class="card-separator">
                            <p class="card-text">Technology is here to stay, Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda harum deserunt magnam aliquam labore tempora eum expedita corrupti ea dolores? Porro voluptatum a dignissimos iste similique ducimus eaque error explicabo!</p>
                        </div>
                    </div>
                </div>
                <!-- Sezione con i due hr e l'H4 centrato -->
                <div class="col-12 text-center mt-5 mb-5">
                    <div class="d-flex align-items-center justify-content-center">
                        <hr class="flex-grow-1 text-white">
                        <h4 class="text-uppercase fs-5 text-secondary mx-3">view all articles</h4>
                        <hr class="flex-grow-1 text-white">
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
    color: #464646;
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
    color: #6b6868;
    text-align: left;
}

.text-white {
    border-color: rgb(255, 252, 252) !important;
}
</style>
