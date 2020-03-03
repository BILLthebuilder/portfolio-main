<template>
<fragment>
    <div class="section light">
    <h2 id="projects" class="subheading">
      Open Source Projects
      <span class="line"></span>
    </h2>
    <div class="center-projects">
      <div class="project-card">
        <div class="heading">
          <h6>Automart</h6>
        </div>
        <div class="body">
          <p>An online car marketplace API</p>
        </div>
        <div class="footer">
          <div>
            <a href="https://automart-api.herokuapp.com/docs/" target="_blank" rel="noopener noreferrer">
              <i class="fa fa-eye"></i> View
            </a>
          </div>
          <a href="https://github.com/BILLthebuilder/automart" target="_blank" rel="noopener">
            <i class="fab fa-github"></i> Repository
          </a>
        </div>
      </div>
      <div class="project-card">
        <div class="heading">
          <h6>Feed-reader</h6>
        </div>
        <div class="body">
          <p>An RSS feeds application that utilizes the Jasmine testing framework for unit tests</p>
        </div>
        <div class="footer">
          <div>
            <a href="https://billthebuilder.github.io/feed-reader" target="_blank" rel="noopener noreferrer">
              <i class="fa fa-eye"></i> View
            </a>
          </div>
          <a href="https://github.com/BILLthebuilder/feed-reader" target="_blank" rel="noopener">
            <i class="fab fa-github"></i> Repository
          </a>
        </div>
      </div>
      <div class="project-card">
        <div class="heading">
          <h6>Nyumbani</h6>
        </div>
        <div class="body">
          <p>A real estate web application </p>
        </div>
        <div class="footer">
          <div>
            <a href="https://billthebuilder.github.io/nyumbani/" target="_blank" rel="noopener noreferrer">
              <i class="fa fa-eye"></i> View
            </a>
          </div>
          <a href="https://github.com/BILLthebuilder/nyumbani" target="_blank" rel="noopener">
            <i class="fab fa-github"></i> Repository
          </a>
        </div>
      </div>
      <div class="project-card">
        <div class="heading">
          <h6>Mawazo</h6>
        </div>
        <div class="body">
          <p>A simple Blogging API</p>
        </div>
        <div class="footer">
          <div>
            <a href="https://auth-api-mongo.herokuapp.com/users/all" target="_blank" rel="noopener noreferrer">
              <i class="fa fa-eye"></i> View
            </a>
          </div>
          <a href="https://github.com/BILLthebuilder/mawazo" target="_blank" rel="noopener">
            <i class="fab fa-github"></i> Repository
          </a>
        </div>
      </div>
      <div class="project-card">
        <div class="heading">
          <h6>Usajili</h6>
        </div>
        <div class="body">
          <p>A user registration system template</p>
        </div>
        <div class="footer">
          <div>
            <a href="https://app-usajili.herokuapp.com/" target="_blank" rel="noopener noreferrer">
              <i class="fa fa-eye"></i> View
            </a>  
          </div>
          <a href="https://github.com/BILLthebuilder/usajili" target="_blank" rel="noopener">
            <i class="fab fa-github"></i> Repository
          </a>
        </div>
      </div>
      <div class="project-card">
        <div class="heading">
          <h6>Restaurant-reviews</h6>
        </div>
        <div class="body">
          <p>An offline first and responsive web application for reviewing restaurants built with pure ES6 Javascript</p>
        </div>
        <div class="footer">
          <div>
            <a href="https://res-review.herokuapp.com/" target="_blank" rel="noopener noreferrer">
              <i class="fa fa-eye"></i> View
            </a>
          </div>
          <a href="https://github.com/BILLthebuilder/restaurant-reviews" target="_blank" rel="noopener">
            <i class="fab fa-github"></i> Repository
          </a>
        </div>
      </div>
    </div>
  </div>
</fragment>    
</template>

<script>
import { Fragment } from 'vue-fragment';

export default {
name:'Projects',
components:{
    Fragment
}    
}
</script>

<style>
.subheading {
  position: relative;
  line-height: 45px;
}
.subheading .line {
  position: absolute;
  left: 0;
  height: 2px;
  width: 100%;
  background-color: rgba(0, 0, 0, 0.8);
  -webkit-transform-origin: 0 0;
  transform-origin: 0 0;
  bottom: 0;
}
.center-projects {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -ms-flex-direction: row;
  flex-direction: row;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  width: 1140px;
}
.project-card {
  display: -webkit-inline-box;
  display: -ms-inline-flexbox;
  display: inline-flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  background-color: #ffffff;
  border-radius: 3px;
  -webkit-box-shadow: 0 1px 3px rgba(0, 0, 0, 0.12),
    0 1px 2px rgba(0, 0, 0, 0.24);
  box-shadow: 0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24);
  width: 300px;
  margin: 15px;
}

.project-card > .heading {
  height: 130px;
  padding: 10px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-flex: 0;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  background-color:  #213377;
  color: white;
}
.project-card > .heading > h6 {
  text-align: center;
  font-size: 1.3em;
  margin: 0;
}
.project-card > .body {
  min-height: 60px;
  padding: 20px 10px;
  -webkit-box-flex: 1;
  -ms-flex: 1;
  flex: 1;
}
.project-card > .body > p {
  margin: 0;
  font-size: 14px;
}
.project-card > .footer {
  background-color: #f4f4f4;
  border-top: 1px solid #cccccc;
  padding: 10px;
  font-size: 12px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-flex: 0;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -ms-flex-direction: row;
  flex-direction: row;
  -webkit-box-pack: justify;
  -ms-flex-pack: justify;
  justify-content: space-between;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}
.project-card > .footer > div {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -ms-flex-direction: row;
  flex-direction: row;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
}
.project-card > .footer a {
  color: rgba(0, 0, 0, 0.8);
  text-decoration: none;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -ms-flex-direction: row;
  flex-direction: row;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-pack: center;
  -ms-flex-pack: center;
  justify-content: center;
}
.project-card > .footer i {
  font-size: 15px;
  margin-right: 8px;
}
.project-card > .footer .framework {
  margin: 0;
}

</style>
