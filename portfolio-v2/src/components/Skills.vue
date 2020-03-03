<template>
    <div class="section light">
    <h2 class="subheading">
      Professional Skills
      <span class="line"></span>
    </h2>
    <div class="skills">
      <div class="skills-section">
        <h3>Languages</h3>
        <ul>
          <li>JavaScript</li>
          <li>NodeJS</li>
          <li>SQL</li>
          <li>Python</li>
        </ul>
      </div>
      <div class="skills-section">
        <h3>Web Frameworks</h3>
        <ul>
          <li>React</li>
          <li>Vue</li>
          <li>Flask</li>
          <li>Django</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name:'Skills'
}
</script>

<style>
.skills {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -ms-flex-direction: row;
  flex-direction: row;
  width: 100%;
  max-width: 1140px;
}
.skills .skills-section {
  -webkit-box-flex: 1;
  -ms-flex: 1 0 auto;
  flex: 1 0 auto;
  text-align: center;
}

ul {
  padding: 0;
}
ul li {
  list-style-type: none;
}

</style>
