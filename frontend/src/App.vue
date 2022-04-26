<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/books">Books</router-link>|
    <router-link to="/categories">Categories</router-link>|
    <router-link to="/about">About</router-link>|
    <router-link to="/signin">Sign in</router-link>|
    <router-link to="/signup">Sign up</router-link>
  </nav>
  <router-view/>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
