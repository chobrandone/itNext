<template>
  <div class="hello">
  <Header/>
  </div>
</template>

<script>
import Header from '../../components/header/header.vue'
export default {
  name: 'Home',
  props: {
    msg: String
  },
    components: {
    Header
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
