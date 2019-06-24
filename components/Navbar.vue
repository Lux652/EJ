<template>
  <div>
    <b-navbar toggleable="lg">
      <b-col cols="1"></b-col>
      <b-col cols="2">
        <b-navbar-brand href="#">
          <img src="../assets/logo.png" alt>
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
}
.ej-nav.hover {
  color: #0322dc !important;
}
</style>
