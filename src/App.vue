<template>
  <div id="wrapper">
    <nav class="navbar is-dark">
      <div class="navbar-brand">
        <router-link to="/" class="navbar-item"><strong>CRUD App</strong></router-link>
      </div>
      <div class="navbar-menu">
        <div class="navbar-end">
            <div class="navbar-item">
              <router-link to="/" class="navbar-item">Home</router-link>
              <div class="buttons">
                <router-link to="/sign-up" class="button is-success"><strong>Link 1</strong></router-link>
              </div>
            </div>

        </div>
      </div>
    </nav>

    <section class="section">
      <router-view/>
    </section>
    <footer class="footer">
      <p class="has-text-centered">Copyright (c) 2021</p>
    </footer>
  </div>
</template>

<script>
  export default {
    name: 'App'
  }
</script>

<style lang="scss">
@import '../node_modules/bulma';
</style>