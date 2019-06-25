<template>
  <div class="guzica">
    <b-navbar toggleable="lg">
      <b-col cols="1"></b-col>
      <b-col cols="2">
        <b-navbar-brand href="#">
          <nuxt-link to="/">
            <img src="../assets/logo-white.png" alt>
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
              <img src="../assets/be-white.png" alt>
            </b-nav-item>
            <b-nav-item class="ej-nav" href="#">
              <img src="../assets/dr-white.png" alt>
            </b-nav-item>
            <b-nav-item class="ej-nav" href="#">
              <img src="../assets/ig-white.png" alt>
            </b-nav-item>
          </b-navbar-nav>
        </b-col>
      </b-collapse>
    </b-navbar>
  </div>
</template>


<style scoped>
.ej-nav {
  color: #fff !important;
  padding-right: 2em;
  font-family: public_sanslight;
}
.ej-nav.hover {
  color: #fff !important;
}
a {
  color: #fff !important;
}
a:hover {
  color: #fff !important;
  text-decoration: none !important;
}
.guzica {
  background-color: #0322dc;
  margin-top: 15em;
  padding-top: 4em;
  padding-bottom: 4em;
}
</style>
