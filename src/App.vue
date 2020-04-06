<template>
  <div id='root'>
    <img src='./logo.png' />
    <div id='nav'>
      <router-link to='/'> Home</router-link>
      <router-link to='/contact'>Contact </router-link>
    </div>
    <router-view />
  </div>
</template>

<script>
import { ref } from 'vue'

export default {
 
}
</script>

<style scoped>

#root {
  text-align: center;
  font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

img {
  width: 200px;
}

#nav {
  font-size: 1.5em;
  margin-bottom: 30px;
}

a {
  text-decoration: none;
  margin: 30px 25px;
  color: #333;
}

a:hover {
  text-decoration: underline;
  color: 
}

</style>
