<template lang="html">
  <div id="nav" class="nav">
    <router-link class="page-label" to="/">VITALY SEVEROV</router-link>
    <div class="menu">
      <router-link to="/series" class="menu__link">Series</router-link>
      <router-link to="/books" class="menu__link">Books</router-link>
      <router-link to="/about" class="menu__link">About</router-link>
      <router-link to="/contact" class="menu__link">Contact</router-link>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped >
.nav {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.menu {
  &__link {
    margin-left: 20px;
  }
}
</style>
