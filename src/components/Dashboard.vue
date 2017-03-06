<template>
<div class="container">
<navigation>
</navigation>
<hero-card>
</hero-card>
<div class ="columns">
<aside-bar>
</aside-bar>
<the-body>
</the-body>
</div>
<site-footer>
</site-footer>
</div>
</template>

<script>
import Navigation from './Navigation'
import HeroCard from './HeroCard'
import SiteFooter from './SiteFooter'
import AsideBar from './AsideBar'
import TheBody from './TheBody'
export default {
  name: 'dashboard',
  components: {
    HeroCard,
    Navigation,
    SiteFooter,
    AsideBar,
    TheBody
  }
}
</script>

<style lang="scss">

$letterscolor: green;

h1 {
  color: $letterscolor;
}

.columns {
    margin-left: .5rem;
    margin-right: -0.75rem;
    margin-top: .5rem;
}

.footer {
    background-color: whitesmoke;
    padding: 3rem 1.5rem 3rem;
}

</style>
