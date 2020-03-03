<template>
    <Portfolio/>
</template>

<script>
import Portfolio from './components/Portfolio.vue'

export default {
  name: 'App',
  components: {
    Portfolio
  }
}
</script>

<style>
html,
body {
  height: 100%;
  width: 100%;
  margin: 0;
  font-family: 'PT Mono', monospace;
}
@media (max-width: 1140px) {
  .center-projects {
    width: 100%;
  }
}

@media (max-width: 540px) {
  .hero .ml1 {
    font-size: 3em;
  }
  .hero .ml16 {
    font-size: 1.5em;
  }
  .section {
    padding: 15px;
  }
  .subheading {
    font-size: 1.2em;
  }
  .skills {
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
  }
  .skills .skills-section {
    -webkit-box-flex: 1;
    -ms-flex: 1 0 100%;
    flex: 1 0 100%;
  }
}
@media (max-width: 420px) {
  .hero .ml1 {
    font-size: 2.5em;
  }
  .hero .ml16 {
    font-size: 1em;
  }
}
@media (max-width: 350px) {
  .hero .ml1 {
    font-size: 2.2em;
  }
}
</style>
