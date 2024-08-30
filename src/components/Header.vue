<script>
export default {
    
}
</script>

<template>
    <div class="container-full">
        <div class="row">
            <div class="col-12 border">
                <div class="d-flex justify-content-between align-items-center px-4 py-4">
                    <img class="img-fluid border" src="../assets/img/construction_logo.png" alt="Avada construction Logo">
                    <ul class="list-unstyled d-flex align-items-center">
                        <li class="px-4 "><a class="text-decoration-none text-dark text-uppercase" href="#">Home</a></li>
                        <li class="px-4 "><a class="text-decoration-none text-dark text-uppercase" href="#">About</a></li>
                        <li class="px-4 "><a class="text-decoration-none text-dark text-uppercase" href="#">Services</a></li>
                        <li class="px-4 "><a class="text-decoration-none text-dark text-uppercase" href="#">Work</a></li>
                        <li class="px-4 "><a class="text-decoration-none text-dark text-uppercase" href="#">Articles</a></li>
                        <li><button class="px-4 text-uppercase btn" href="#">Get Quote</button></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    @use "../components/style/partials/vars" as *;

    li:hover{
        color:  $yellow ;
    }

    button {
        background-color: $yellow;
        padding: 5px 40px;
      }

</style>