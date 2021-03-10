<template>  
   <div>
      <NavBar/>
      <Banner/>
   </div>
</template>

<script>
import NavBar from './NavBar.vue'
import Banner from '../components/Banner.vue'

export default {
  name: 'Inicial',
  components: {
    NavBar,
    Banner
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
