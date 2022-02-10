<template>

  <Header />

  <router-view/>
</template>

<style>
* {
  margin: 0;
  padding: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

</style>

<script>
// @ is an alias to /src
import Header from '@/components/header.vue'

export default {
  name: 'Home',
  components: {
    Header
  }
}
</script>