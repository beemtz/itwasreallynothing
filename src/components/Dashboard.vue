<template>
<div>
<h1>{{ header }}</h1>
</div>
</template>

<script>
export default {
  name: 'dashboard',
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
