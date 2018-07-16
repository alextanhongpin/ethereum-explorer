<template>
  <div>
    <div>Home Page</div>
    <SearchBar/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import SearchBar from '@/components/SearchBar.vue'

@Component({
  components: {
    SearchBar
  },
})
export default class Home extends Vue {}
</script>


<style scoped lang='scss'>
</style>