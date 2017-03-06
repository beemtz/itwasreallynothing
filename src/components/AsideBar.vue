<template>
  <div class="column is-3">
    <aside class="menu">
      <p class="menu-label">Aside Title</p>
      <ul class="menu-list">
        <li><a>Item</a></li>
        <li><a>Other Item</a></li>
        <li><a>Thing</a></li>
        <li><a>Other Thing</a></li>
        <li><a>Thingy Item</a></li>
      </ul>
    </aside>
  </div>
</template>

<script>
export default {
  name: 'aside-bar',
  data () {
    return {
      header: 'Welcome to Movie Phone'
    }
  }
}
</script>

<style lang="scss" scoped>

$letterscolor: white; /*why is this getting overwritten?*/

h1 {
  color: $letterscolor;
}

</style>
