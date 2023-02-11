<template>
  <div>
    <NavBar/>
    <Services/>
    <About-us/>
    <Contact/>
    <Footer/>
  </div>
</template>

<script>
import AboutUs from '../components/tiencil/AboutUs.vue';
import Contact from '../components/tiencil/Contact.vue';
import Footer from '../components/tiencil/Footer.vue';
import NavBar from '../components/tiencil/NavBar.vue';
import Services from '../components/tiencil/Services-t.vue';

export default {
    name: "IndexPage",
    components: { NavBar, Services, AboutUs, Contact, Footer }
}
</script>
