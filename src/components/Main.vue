<script>
import Jumbo from './partials/Jumbo.vue';
import Bottom from "./partials/Bottom.vue";
import Trusted from "./partials/Trusted.vue";
    export default {
        components: {
            Jumbo,
            Bottom,
            Trusted,


    }
}
</script>

<template>
    <div class="main">
        <Jumbo />
        <Trusted />
        <Bottom />
    </div>
</template>

<style lang="scss" scoped>
</style>