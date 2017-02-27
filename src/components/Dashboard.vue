<template>
<div class="container">
<navigation>
</navigation>
<aside-bar>
</aside-bar>
<site-footer>
</site-footer>
</div>
</template>

<script>
import Navigation from './Navigation'
import SiteFooter from './SiteFooter'
import AsideBar from './AsideBar'
export default {
  name: 'dashboard',
  components: {
    Navigation,
    SiteFooter,
    AsideBar
  }
}
</script>

<style>
h1 {
  color: blue;
}
</style>
