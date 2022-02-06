<template>
  <div id="header">
    <h1 class="logo"> Théo</h1>
    <nav>
      <router-link class="link" to="/">Home</router-link> 
      <router-link class="link" to="/about">Project</router-link>
      <router-link class="link" to="/about">Contact</router-link>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#header {
  width: 100%;
  background-color: #343434;
  height: 100px;
  display: flex;
  align-items: center;
  padding-left: 25px;
  justify-content: space-between;
}

.link , .link:hover , link:focus , link:active{
  margin-right: 130px;
  text-decoration: none;
  font-family: 'Passion One', cursive;

  font-size: 58px;
  color: white
}

#header .logo {
  font-size: 58;

}


</style>
