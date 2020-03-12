<template>

    <header>
    <nav class="navbar is-fixed-top" role="navigation" aria-label="main navigation">
      <div class="container">
  <div class="navbar-brand">

    <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" @click="isOpen = !isOpen" v-bind:class="{'is-active': isOpen}" data-target="mainNav">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>

  <div id="mainNav" class="navbar-menu" v-bind:class="{'is-active': isOpen}">

    <div class="navbar-end">
        <nuxt-link to="/" class="navbar-item">
        About
        </nuxt-link>
        <nuxt-link to="work" class="navbar-item">
        Work
        </nuxt-link>
      <div class="navbar-item">
          <a class="button is-primary" href="mailto: heyannagallo@gamil.com">
            Contact
          </a>
      </div>
    </div>
  </div>
  </div>
</nav>

    </header>

</template>

<script>
export default {
    data: function() {
        return {
            isOpen: false
        }
    }
}
</script>

<style lang="scss">
    @import '~assets/css/main.scss';
    .logo {
      background-color: $black;
      color: $white!important;
    }

</style>