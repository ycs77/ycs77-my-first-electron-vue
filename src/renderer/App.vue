<template>
  <div id="#app" class="text-center">
    <div id="nav" class="nav">
      <router-link class="nav-item nav-link" active-class="active" exact to="/">Home</router-link>
      <router-link class="nav-item nav-link" active-class="active" exact to="/about">About</router-link>
    </div>

    <keep-alive>
      <router-view/>
    </keep-alive>
  </div>
</template>

<script>
  export default {
    name: 'my-first-electron-vue'
  }
</script>

<style lang="scss">
#nav {
  justify-content: center;
  a {
    &.active {
      color: #42b983;
    }
  }
}
</style>
