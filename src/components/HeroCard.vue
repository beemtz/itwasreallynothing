<template>
  <section class="hero is-primary is-medium">
    <div class="hero-body">
      <div class="container">
        <h1 class="title">
          Cool Title, Bruh
        </h1>
        <h2 class="subtitle">
          Medium subtitle is medium
        </h2>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'hero-card',
  data () {
    return {
      header: 'Welcome to Movie Phone'
    }
  }
}
</script>

<style>
h1 {
  color: blue;
}
</style>
