<template>
  <fragment>
     <div class="hero">
    <h1 class="ml1">
      <span class="text-wrapper">
        <span class="line line1"></span>
        <span class="letters">Bill Kariri</span>
        <span class="line line2"></span>
      </span>
    </h1>
    <h4 class="ml16">Software Developer</h4>
    <div class="more-button">
      <p>Check out my work!</p>
      <i class="fal fa-chevron-down" @click="greet"></i>
    </div>
  </div>
  </fragment>
</template>

<script>
import { Fragment } from 'vue-fragment';

export default {
    name:'Hero',
    components:{
      Fragment
    },
    methods:{
      greet: function scrollIt() {
            const offset = document.querySelector('.hero').clientHeight - window.scrollY;
             window.scrollBy({
              behavior: 'smooth',
              left: 0,
               top: offset
           });
}
    }
}
</script>

<style>
.hero {
  height: 100%;
  width: 100%;
  background-color: #213377;
  color: #dfe6e9;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}
.ml1 {
  font-weight: 900;
  font-size: 3.5em;
}

.ml1 .letter {
  display: inline-block;
  line-height: 1em;
  opacity: 0;
}

.ml1 .text-wrapper {
  position: relative;
  display: inline-block;
  padding-top: 0.1em;
  padding-right: 0.05em;
  padding-bottom: 0.15em;
}

.ml1 .line {
  opacity: 0;
  position: absolute;
  left: 0;
  height: 2px;
  width: 100%;
  background-color: #fff;
  -webkit-transform-origin: 0 0;
  transform-origin: 0 0;
}

.ml1 .line1 {
  top: 0;
}
.ml1 .line2 {
  bottom: 0;
}

.ml16 {
  /* color: #402d2d; */
  padding: 40px 0;
  font-weight: 800;
  font-size: 2em;
  text-transform: uppercase;
  letter-spacing: 0.3em;
  overflow: hidden;
}

.ml16 .letter {
  display: inline-block;
  line-height: 1em;
  opacity: 0;
}
.more-button {
  text-align: center;
  position: absolute;
  bottom: 15px;
  cursor: pointer;
  /* opacity: 0; */
}

.more-button > .fal {
  font-size: 30px;
}

.more-button > p {
  margin: 0 0 10px 0;
}
</style>
