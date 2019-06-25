<template>
  <div>
    <Navbar/>
    <b-container class="work-ej">
      <b-row>
        <b-col cols="3"></b-col>
        <b-col class="juro" cols="9">
          <h1 class="h1EJ">
            Hi! I'm a digital designer specialized in
            <span class="spanEJ">Brand identity & UI design</span> based in Croatia.
          </h1>
          <b-button class="btnEJ" size="lg" squared variant="outline-secondary">
            <nuxt-link to="contact">CONTACT ME</nuxt-link>
          </b-button>
        </b-col>
      </b-row>
    </b-container>
    <MyWork/>
    <Contact/>
    <Footer/>
  </div>
</template>

<script>
import Navbar from "~/components/Navbar.vue";
import MyWork from "~/components/Mywork.vue";
import Contact from "~/components/Contact.vue";
import Footer from "~/components/Footer.vue";

export default {
  components: {
    Navbar,
    MyWork,
    Contact,
    Footer
  }
};
</script>

<style>
.work-ej {
  margin-top: 200px;
}
.juro {
  left: -177px;
}
.h1EJ {
  font-size: 75px;
  color: #4e4e4e;
  font-family: gilroyextrabold;
}
.spanEJ {
  color: #0322dc;
}
.btnEJ {
  width: 13em;
  color: #4e4e4e;
  border-color: #0322dc !important;
  margin-top: 2em;
}
a {
  color: #4e4e4e !important;
  font-family: public_sanslight;
}
a:hover {
  color: #fff !important;
  text-decoration: none !important;
}
button:hover {
  background-color: red;
}
</style>
