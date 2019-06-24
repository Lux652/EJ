<template>
  <b-container class="cont">
    <b-row>
      <b-col cols="3"></b-col>
      <b-col class="juro" cols="9">
        <h1 class="h1EJ">Contact</h1>
        <h4
          class="h4EJ"
        >If you like what I do, feel free to contact me via e-mail, or check my social media links.</h4>
        <h1 class="mailEJ">ejergovic@gmail.com</h1>
      </b-col>
    </b-row>
    <b-row>
      <b-col cols="3"></b-col>
      <b-col class="soc-icons juro" cols="9">
        <span>
          <img src="../assets/be.png" alt>
        </span>
        <span>
          <img src="../assets/dr.png" alt>
        </span>
        <span>
          <img src="../assets/ig.png" alt>
        </span>
      </b-col>
    </b-row>
  </b-container>
</template>

<style scoped>
.h1EJ {
  font-size: 75px;
  color: #4e4e4e;
}
.mailEJ {
  font-size: 48px;
  color: #4e4e4e;
}
.h4EJ {
  font-size: 21px;
  color: #4e4e4e;
}
.juro {
  left: -177px;
}
.cont {
  margin-top: 9em;
}
.soc-icons {
  margin-top: 2em;
}
span {
  padding-right: 2em;
}
</style>
