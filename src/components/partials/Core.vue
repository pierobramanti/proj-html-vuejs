<script>
import { coreValues } from "../data/components"
export default {
  data() {
    return {
      coreValues,
    };
  },
};
</script>

<template>
  <div class="bg-grey">
    <div class="container">
      <div class="row">
        <div class="col-12 d-flex flex-column align-items-center text-center mt-4">
          <h3 class="fs-3 fw-semibold mb-2">Our Core Values</h3>
          <hr class="fw-bolder mb-3" />
          <h5 class="fs-6 mt-2 mb-4 lh-lg text-secondary">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio
            distinctio reprehenderit quam iusto,<br />sint nulla omnis ex
            debitis nisi aspernatur possimus repellendus adipisci
          </h5>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="row d-flex justify-content-between mt-4 gap-4">
        <div
          class="col d-flex flex-column align-items-center text-center"
          v-for="value in coreValues"
          :key="value.id"
        >
          <div
            :class="['icon-circle', value.bgColor, 'd-flex', 'justify-content-center', 'align-items-center', 'mb-3']"
          >
            <i :class="['fs-3', value.icon, 'text-white']"></i>
          </div>
          <h4 class="fw-lighter text-grey fs-5">{{ value.title }}</h4>
          <hr class="hr-custom fw-bolder mb-3" />
          <p class="text-secondary">{{ value.text }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use "../style/partials/vars" as *;


hr {
  width: 150px;
  color: $yellow;
  border: solid 2px;
}

.hr-custom {
  width: 20px;
  border-color: $black;
}

.icon-circle {
  width: 70px;
  height: 70px;
  border-radius: 50%;
  transition: background-color 0.3s;
  cursor: pointer;
}

.icon-circle:hover {
  background-color: $yellow;
}


.text-white {
  color: $white;
}
</style>
