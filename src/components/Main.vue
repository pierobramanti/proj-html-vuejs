<script>
import Jumbo from './partials/Jumbo.vue';
import Bottom from "./partials/Bottom.vue";
import Trusted from "./partials/Trusted.vue";
import Latest from "./partials/Latest.vue"
    export default {
        components: {
            Jumbo,
            Bottom,
            Trusted,
            Latest,


    }
}
</script>

<template>
    <div class="main">
        <Jumbo />
        <Latest />
        <Trusted />
        <Bottom />
    </div>
</template>

<style lang="scss" scoped>
</style>