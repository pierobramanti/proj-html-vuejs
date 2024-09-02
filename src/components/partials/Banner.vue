<script>
export default {
    
}
</script>

<template>
    <div class="bg-yellow">
        <div class="container">
            <div class="row">
                <div class="col-12 d-flex flex-column justify-content-center align-items-center text-center mt-4">
                    <h2 class=" fw-light fs-2">Do You Have a Construction Project We Can Help With?</h2>
                    <button class="px-4 text-uppercase text-white mt-3" href="#">Get a Free Quote</button>
                </div>
            </div>
          </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../style/partials/vars" as *; 
.container{
    height: 100px;
}

button {
    background-color: $black;
    padding: 5px 40px;
    outline: none;
    border: none;
  
    &:hover {
      background-color: $yellow;
      color: $grey;
    }
  }

</style>