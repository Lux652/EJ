<template>
  <div class="guzica">
    <b-navbar toggleable="lg">
      <b-col cols="1"></b-col>
      <b-col cols="2">
        <b-navbar-brand href="#">
          <img src="../assets/logo-white.png" alt>
        </b-navbar-brand>
      </b-col>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-col cols="9">
          <b-navbar-nav>
            <b-nav-item class="ej-nav" href="#">WORK</b-nav-item>
            <b-nav-item class="ej-nav" href="#">ABOUT ME</b-nav-item>
            <b-nav-item class="ej-nav" href="#">CONTACT</b-nav-item>
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
.navbar-light .navbar-nav .nav-link {
  color: #fff !important;
}
.ej-nav.hover {
  color: #0322dc !important;
}
.guzica {
  background-color: #0322dc;
  margin-top: 15em;
  padding-top: 4em;
  padding-bottom: 4em;
}
.ej-nav {
  padding-right: 2em;
}
</style>
