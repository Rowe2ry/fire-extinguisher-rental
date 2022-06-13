<template>
  <div>
    Hello I am /products/id
    {{ products }}
  </div>
</template>

<script>
import { mapState } from "vuex";
  export default {
    computer: {
      ...mapState([
        'products'
      ])
    }
  }
</script>

<style scoped>

</style>
