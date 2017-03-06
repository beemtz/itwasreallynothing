<template>
  <div class="column">
  <div class="tile is-ancestor">
  <div class="tile is-vertical is-8">
    <div class="tile">
      <div class="tile is-parent is-vertical">
        <article class="tile is-child notification is-danger">
          <p class="title">Vertical...</p>
          <p class="subtitle">Top tile</p>
        </article>
        <article class="tile is-child notification is-warning">
          <p class="title">...tiles</p>
          <p class="subtitle">Bottom tile</p>
        </article>
      </div>
    </div>
  </div>
  <div class="tile is-parent">
    <article class="tile is-child notification is-info">
      <p class="title">Self-Esteem LolCat</p>
      <figure class="image is-4by3">
        <img src="http://www.lolcats.com/images/u/12/43/lolcatsdotcomlikemyself.jpg">
      </figure>
    </article>
  </div>
</div>
</div>
</template>

<script>
export default {
  name: 'the-body',
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
