<template>
  <header>{{brand}}</header>
</template>

<script lang='ts'>
import { Component, Vue, Prop } from 'vue-property-decorator'

@Component
export default class AppHeader extends Vue {
  @Prop() private brand!: string;
}
</script>

<style scoped lang="scss">
  header {
    font-weight: bold;
    padding: 15px 30px;
    font-size: 1.5rem;
  }
</style>