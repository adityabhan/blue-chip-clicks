<template>
  <div class="hello">
    <NavBar />
    <div id="first-look">
      <h1>We blend creativity with media & technology to grow faster</h1>
    </div>

    <div><About /></div>

    <div><Services /></div>
    <div><Portfolio /></div>
    <div><Contact /></div>

    <Footer />
  </div>
</template>

<script>
import NavBar from "./Navigation/Navbar.vue";
import Footer from "./Footer/Footer.vue";
import About from "./About/About.vue";
import Services from "./Services/Services.vue";
import Portfolio from "./Portfolio/Portfolio.vue";
import Contact from "./ContactUs/Contact.vue";

export default {
  name: "HelloWorld",
  components: {
    NavBar,
    Footer,
    About,
    Services,
    Portfolio,
    Contact,
  },
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

#first-look {
  background: white;
  padding: 20% 0% 20% 15%;
}
</style>
