<script>
import { items } from "../data/components"

export default {
  data() {
    return {
      items,
    };
  },
};
</script>

<template>
  <div class="bg-numbers position-relative">
    <div class="container h-100 d-flex align-items-center justify-content-center">
      <div class="row min-vh-100 d-flex justify-content-center align-items-center">
        <div class="col-12 d-flex justify-content-center align-items-center text-center gap-3">
          <div
            class="col-4"
            v-for="(item, index) in items"
            :key="index"
          >
            <i :class="item.icon + ' color-yellow fs-1 mb-1'"></i>
            <h3 class="color-yellow fs-1">{{ item.number }}</h3>
            <p class="text-uppercase text-white">{{ item.text }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "../style/partials/vars" as *;

.color-yellow {
  color: $yellow;
}

.bg-numbers {
  background-image: url("../../assets/img/home-244125289.jpg");
  background-size: cover;
  height: 550px;
  background-position: center;
  position: relative;
  overflow: hidden;

  &:before,
  &:after {
    content: '';
    position: absolute;
    width: 100%;
    height: 50px;
    background: $white; 
  }

  &:before {
    top: 0;
    transform: translateY(-10%);
    border-radius: 0 0 100% 100%; 
  }

  &:after {
    bottom: 0;
    transform: translateY(10%);
    border-radius: 100% 100% 0 0; 
  }
}

hr {
  width: 30px;
  color: $yellow;
  border: solid 2px;
}
</style>
