<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang="scss">
@import "~assets/styles/vars";
@import "~bulma";
@import "~assets/styles/main";
body {
  background: $useless;
}
</style>
