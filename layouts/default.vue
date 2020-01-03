<template>
  <div>
    <header-section />
    <nuxt />
    <footer-section />
  </div>
</template>

<script>
import header from '~/components/header.vue'
import footer from '~/components/footer.vue'
export default {
  components: {
    headerSection: header,
    footerSection: footer
  }
}
</script>
<style>

</style>
