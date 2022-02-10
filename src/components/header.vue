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
  justify-content: space-between;
  max-width: 100vw;
}

.logo {
  color: white;
  margin-left: 25px;
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

a.router-link-exact-active {
  text-decoration: underline;
}

@media screen and (max-width: 1000px) {

  #header {
    width: 100%;
    background-color: #343434;
    height: auto;
    display: flex;
    align-items: center;

    padding-left: 25px;
    padding: 25px 0;

    justify-content: space-between;
    flex-direction: column;
  }

  .link , .link:hover , link:focus , link:active{
    margin-right: 0;
  }

  #header nav {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding-left: 0;
    margin-top: 25px;
  }

  .logo {
  margin-left: 0;
  }
}



</style>
