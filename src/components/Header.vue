<script>
import { menuItems } from "../../src/components/data/components"
export default {
    data() {
        return {
            menuItems,
        }
    }
}
</script>

<template>
    <div class="container">
        <div class="row">
            <div class="col-12 ">
                <div class="d-flex justify-content-between align-items-center px-4 py-3">
                    <img class="img-fluid" src="../assets/img/construction_logo.png" alt="Avada construction Logo">
                    <ul class="list-unstyled d-flex align-items-center">
                        <li v-for="item in menuItems" :key="item.label" class="px-4" :class="{ 'active-class': item.isActive }">
                            <a class="text-decoration-none text-dark text-uppercase fw-semibold" :href="item.link">{{ item.label }}</a>
                        </li>
                        <li><button class="px-4 text-uppercase" href="#">Get Quote</button></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    @use "../components/style/partials/vars" as *;

    li:hover a {
        color: $yellow !important;
    }

    button {
        background-color: $yellow;
        padding: 5px 40px;
        border: none;
        outline: none;

        &:hover {
            background-color: $light_black;
            color: $grey;
        }
    }

</style>