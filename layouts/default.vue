<template>
  <div>
    <header-section />
    <nuxt />
  </div>
</template>

<script>
import header from '~/components/header.vue'
export default {
  components: {
    headerSection: header
  }
}
</script>
<style>

</style>
