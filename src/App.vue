<template>
  <div id="app">
    <AppHeader brand='Ƀlockcoin'/>
    <AppNavbar/>
    <router-view/>
  </div>
</template>


<script lang='ts'>
import { Component, Vue } from 'vue-property-decorator'
import AppHeader from '@/components/AppHeader.vue'
import AppNavbar from '@/components/AppNavbar.vue'

@Component({
  components: {
    AppHeader,
    AppNavbar
  },
})
export default class App extends Vue {}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

input {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
}

:root {
  --gallery: #EEEEEE;
}
</style>
