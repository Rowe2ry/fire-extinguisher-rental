<template>
  <div>
    <MyItem
      v-for="myItem in myRentals"
      :key="myItem.id"
      :item="myItem"
    />
  </div>
</template>

<script>
import { mapState } from 'vuex';
  export default {
    layout: 'no-nav',
    computed: {
      ...mapState(['myRentals'])
    }
  }
</script>

<style scoped>

</style>
