<template>
<div>
    <li>
      <ul><a href="">Futsal</a></ul> 
      <ul><a href="">Futbol 11</a></ul>
      <ul><a href="">Contacto</a></ul>
  </li>
  </div>
  
</template>

<script>
export default {
name: "NavBar"
}
</script>

<style  scoped>
div{
    
}
li{
    list-style: none;
    
  line-height: 10px;
  color: white;
  font-weight: bold;
  font-size: 2em;
  text-align: center;
  display: inline-flex;
  text-decoration: none;
}
a:link, a:visited, a:active {
    text-decoration:none;
    color: gray;
    font-size: 60%;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
</style>