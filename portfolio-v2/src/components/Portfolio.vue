<template>
<fragment>
   <Hero/>
   <Projects/>
   <Skills />
   <Footer />
</fragment>
</template>

<script>
import { Fragment } from 'vue-fragment';
import Hero from './Hero';
import Projects from './Projects';
import Skills from './Skills';
import Footer from './Footer';
export default {
  name: 'Portfolio',
  components:{
  Fragment,
  Hero,
  Projects,
  Skills,
  Footer
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.section {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: start;
  -ms-flex-pack: start;
  justify-content: flex-start;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  padding: 40px;
}
.section.light {
  background-color: #dfe6e9;
  color: rgba(0, 0, 0, 0.8);
}
.section.dark {
  background-color: #213377;
  color: #dfe6e9;
}
</style>
