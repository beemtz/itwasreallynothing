<template>
  <nav class="nav">
    <div class="nav-left">
      <a class="nav-item">
        <h1>{{ header }}</h1>
      </a>
    </div>
    <!-- This "nav-toggle" hamburger menu is only visible on mobile -->
    <!-- You need JavaScript to toggle the "is-active" class on "nav-menu" -->
    <span class="nav-toggle">
      <span></span>
      <span></span>
      <span></span>
    </span>
    <!-- This "nav-menu" is hidden on mobile -->
    <!-- Add the modifier "is-active" to display it on mobile -->
    <div class="nav-right nav-menu">
      <a
      :href="thing.slug"
      v-for="thing in menuThings"
      v-if="thing.slug"
      class="nav-item">
      {{ thing.name }}
    </a>
  </div>
</nav>
</template>

<script>
export default {
  name: 'navigation',
  data () {
    return {
      header: 'Welcome to Movie Phone',
      menuThings: [
        {
          name: 'Home',
          slug: 'home'
        },
        {
          name: 'Documentation',
          slug: 'docs'
        },
        {
          name: 'Blog',
          slug: 'blog'
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

$letterscolor: #515135;

h1 {
  color: $letterscolor;
}

</style>
