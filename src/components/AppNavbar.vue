<template>
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/contracts">Contracts</router-link> | 
      <router-link to="/contracts">Events</router-link> | 
      <router-link to="/contracts">Past Events</router-link>
    </div>
</template>

<style scoped lang='scss'>
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
</style>