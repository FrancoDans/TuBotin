<template>

  <div class="hello">
   
    <h1><span>Tu</span>Botin</h1>
    <h2><NavBar/></h2>
  </div>
  
</template>

<script>
import NavBar from '@/components/NavBar.vue'
export default {

  name: 'HelloWorld',
  components: {
  NavBar
  },
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  
  h1{
  color:white;
  font-size: 50px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-weight: bold;
}

h1 span{
  transition: .5s linear;
}

h1:hover span{
  margin-right: 20px;
}


</style>
