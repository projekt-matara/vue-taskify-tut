<template lang="pug">
  #app
    Navbar
    router-view
</template>

<script>
import Navbar from './components/Navbar'
export default {
  name: 'app',
  components: {Navbar}
}
</script>

<style lang="stylus">
html
  background-color #FAFAFA
</style>
