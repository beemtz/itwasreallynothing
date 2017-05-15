<template>
  <div class="column is-3">
    <aside class="menu">
      <p class="menu-label">Aside Title</p>
      <ul class="menu-list">
        <li><a class="special-item">  <a
          :href="stuff.slug"
          v-for="stuff in asideStuff"
          class="nav-item">
          {{ stuff.name }}
        </a></li>
        <!-- ISSUE HERE! Since it's all in a single <li>/<a>, everything moves at the same time-->
      </ul>
    </aside>
  </div>
</template>

<script>
export default {
  name: 'aside-bar',
  data () {
    return {
      header: 'Welcome to Movie Phone',
      asideStuff: [
        {
          name: 'Item'
        },
        {
          name: 'Other Item'
        },
        {
          name: 'Thing'
        },
        {
          name: 'Other Thing'
        },
        {
          name: 'Thingy Item'
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
@import "~assets/styles/vars";

$letterscolor: white;

ul.menu-list {
background-color: $info;
  a {
    position: relative;
    left: 0;
    transition: all 2000ms;
    background-color: transparent;
    color: $letterscolor;
    &.special-item {
      color: $primary;
    }
    &:hover {
      left: 100px;
      background-color: $danger;
      color: $warning;
    }
  }
}

</style>
