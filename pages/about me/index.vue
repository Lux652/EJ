<template>
  <div>
    <Navbar/>
    <b-container class="about-ej">
      <b-row>
        <b-col cols="7" class="imgEJ">
          <img src="../../assets/enio.png" alt>
        </b-col>
        <b-col class="aboutEJ" cols="5">
          <h1 class="h1EJ">Hi! I'm Enio</h1>
          <br>
          <h4 class="h4EJ">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptatem expedita architecto laboriosam, ipsa illum eaque? Eaque corrupti beatae sunt cum et unde impedit odit. Odit quo rem aliquid inventore illum repudiandae quibusdam reiciendis! Molestiae tempora atque magnam quisquam suscipit? Optio, debitis. Facere, perspiciatis totam aspernatur aperiam, ex, ullam harum minima eaque deleniti sit enim aliquam! Nemo ipsum exercitationem, temporibus ullam quidem deleniti, saepe ea sint ex iusto aspernatur totam odio facere eligendi repudiandae aperiam rem, voluptatem tenetur tempore incidunt.
            <br>
            <br>Ad ab corporis sed dolor perspiciatis numquam corrupti rem!
          </h4>
        </b-col>
      </b-row>
      <Timeline/>
    </b-container>
    <Contact/>
    <Footer/>
  </div>
</template>
<script>
import Navbar from "~/components/Navbar.vue";
import Contact from "~/components/Contact.vue";
import Footer from "~/components/Footer.vue";
import Timeline from "~/components/Timeline.vue";

export default {
  components: {
    Navbar,
    Contact,
    Footer,
    Timeline
  }
};
</script>

<style scoped>
.about-ej {
  margin-top: 120px;
}
.imgEJ {
  left: -20px;
}
.h1EJ {
  font-size: 75px;
  color: #4e4e4e;
}
.aboutEJ {
  margin-top: 25px;
}
.h4EJ {
  font-family: public_sansregular;
  color: #4e4e4e;
}
</style>
