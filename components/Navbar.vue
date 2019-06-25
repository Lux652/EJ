<template>
  <div>
    <b-navbar toggleable="lg">
      <b-col cols="1"></b-col>
      <b-col cols="2">
        <b-navbar-brand href="#">
          <nuxt-link to="/">
            <img src="../assets/logo.png" alt>
          </nuxt-link>
        </b-navbar-brand>
      </b-col>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-col cols="9">
          <b-navbar-nav>
            <b-nav-item class="ej-nav">
              <nuxt-link to="/" exact>WORK</nuxt-link>
            </b-nav-item>
            <b-nav-item class="ej-nav">
              <nuxt-link to="about me">ABOUT ME</nuxt-link>
            </b-nav-item>
            <b-nav-item class="ej-nav" href="#">
              <nuxt-link to="contact">CONTACT</nuxt-link>
            </b-nav-item>
          </b-navbar-nav>
        </b-col>
        <b-col>
          <b-navbar-nav class="ml-auto">
            <b-nav-item class="ej-nav" href="#">
              <img src="../assets/be.png" alt>
            </b-nav-item>
            <b-nav-item class="ej-nav" href="#">
              <img src="../assets/dr.png" alt>
            </b-nav-item>
            <b-nav-item class="ej-nav" href="#">
              <img src="../assets/ig.png" alt>
            </b-nav-item>
          </b-navbar-nav>
        </b-col>
      </b-collapse>
    </b-navbar>
  </div>
</template>


<style scoped>
.ej-nav {
  color: #4e4e4e !important;
  padding-right: 2em;
  font-family: public_sanslight;
}
.ej-nav.hover {
  color: #0322dc !important;
}
a {
  color: #4e4e4e !important;
}
a:hover {
  color: #0322dc !important;
  text-decoration: none !important;
}
</style>
