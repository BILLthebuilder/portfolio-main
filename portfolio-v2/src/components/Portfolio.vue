<template>
<fragment>
   <Hero/>
   <Projects/>
</fragment>
</template>

<script>
import { Fragment } from 'vue-fragment';
import Hero from './Hero';
import Projects from './Projects';
export default {
  name: 'Portfolio',
  components:{
  Fragment,
  Hero,
  Projects
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

</style>
