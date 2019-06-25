<template>
  <div>
    <Navbar/>
    <Contact/>
    <Footer class="footer"/>
  </div>
</template>
<script>
import Navbar from "~/components/Navbar.vue";
import Contact from "~/components/Contact.vue";
import Footer from "~/components/Footer.vue";

export default {
  components: {
    Navbar,
    Contact,
    Footer
  }
};
</script>

<style scoped>
.footer {
  position: absolute !important;
  width: 100% !important;
  bottom: 0 !important;
}
</style>
