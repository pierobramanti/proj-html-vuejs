<script>
import Jumbo from './partials/Jumbo.vue';
import Bottom from "./partials/Bottom.vue";
import Trusted from "./partials/Trusted.vue";
import Latest from "./partials/Latest.vue";
import Carousel from './partials/Carousel.vue';
import Core from "./partials/Core.vue";
import Recent from "./partials/Recent.vue";
import Numbers from './partials/Numbers.vue';
import Modern from "./partials/Modern.vue";
import Banner from './partials/Banner.vue';
    export default {
        components: {
            Jumbo,
            Bottom,
            Trusted,
            Latest,
            Carousel,
            Core,
            Recent,
            Numbers,
            Modern,
            Banner,


    }
}
</script>

<template>
    <div class="main">
        <Jumbo />
        <Banner />
        <Modern />
        <Numbers />
        <Recent />
        <Core />
        <Carousel />
        <Latest />
        <Trusted />
        <Bottom />
    </div>
</template>

<style lang="scss" scoped>


</style>