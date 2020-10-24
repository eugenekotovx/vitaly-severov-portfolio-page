<template>
  <div id="app">
    <NavBar/>
    <router-view/>
  </div>
</template>

<script type="text/javascript">
import NavBar from "@/components/NavBar"
export default {
  components: {
    NavBar
  }
}
</script>
<style lang="scss">
#app {
  font-family: "Open Sans Regular";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
@font-face {
  font-family: "Open Sans Regular";
  src: local("Merienda"),
   url(./assets/fonts/OpenSans-Regular.ttf) format("truetype");
}
</style>
