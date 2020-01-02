<template>
  <div>
    <top-header />
    <main id="main" role="main">
      <nuxt />
    </main>
    <bottom-footer />
  </div>
</template>

<script>
import TopHeader from '@/components/TopHeader'
import BottomFooter from '@/components/BottomFooter'

export default {
  components: { TopHeader, BottomFooter }
}
</script>

/*
<style lang="scss">
// @import '@/assets/scss/styles.scss'; // DGG: It's better to have this as a global file in nuxt.config.js
</style>
*/
