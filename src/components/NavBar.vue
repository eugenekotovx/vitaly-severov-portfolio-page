<template lang="html">
  <div id="nav" class="nav">
    <router-link class="page-label" to="/">VITALY SEVEROV</router-link>
    <div class="menu">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="css" scoped >
.nav {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
</style>
