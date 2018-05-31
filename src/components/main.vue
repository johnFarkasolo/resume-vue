<template>
  <div class="main-body">
    <parallax>
      <div id="skills">
				<img src="assets/img/1.jpg" alt="">
        <h1>
          Skills
        </h1>
        <div id="summary_skills">
          <h2>
            SUMMARY OF SKILLS:
          </h2>
          <ul>
            <li>Front-end Developer with X years of experience designing, developing, and managing complex e-commerce
              sites. Specializes in JS and responsive design
            </li>
            <li>Intermediate English level (written and spoken)</li>
            <li>Strong understanding of industry trends and content management systems</li>
            <li>Ability to improvise, learn new skills in short terms, self-motivated and result-oriented</li>
          </ul>
        </div>
        <div>
          <h2>TECHNICAL SKILLS:</h2>
          <ul>
            <li>Front-end: CSS3, HTML5, XML, web standards and accessibility, cross-browser compatibility, JSON with
              padding
            </li>
            <li>Programming/scripting languages: JavaScript (ES6, jQuery, Bootstrap), basic knowledge of SQL</li>
            <li>DB: Oracle</li>
            <li>Development tools: WebStorm, Note++, Sublime Text, Photoshop/Fireworks, GitHub Desktop</li>
            <li>APIs: Web Storage API, JSON API, Web-Storage API, Web Workers API, Geolocation API, Google Maps
              JavaScript API
            </li>
            <li>Version control systems: Git</li>
          </ul>
        </div>
      </div>
    </parallax>
    <parallax>
      <!--Это лучше сделать галереей-->
      <div id="projects" class="container-fluid">
        <div class="row">
          <div>
            <img src="../assets/projects/1.jpg" alt="">
          </div>
          <div>
            <img src="../assets/projects/1.jpg" alt="">
          </div>
          <div>
            <img src="../assets/projects/1.jpg" alt="">
          </div>
          <div>
            <img src="../assets/projects/1.jpg" alt="">
          </div>
          <div>
            <img src="../assets/projects/1.jpg" alt="">
          </div>
        </div>
      </div>
    </parallax>
    <parallax>
      <div id="contacts">
        <ul>
          <li>tel. +48 ********* Cell Phone</li>
          <li>Viber +48 ********** Viber</li>
          <li>Skype *********</li>
          <li>email ********.com</li>
          <li>Github www.github.com/*******</li>
          <li>facebook www.facebook.com/********</li>
          <li>location **************</li>
        </ul>
      </div>
    </parallax>
  </div>
</template>

<script>
  export default {
    name: "main"
  }
</script>

<style lang="scss" scoped>
  @import '../styles/variables';

  * {
    color: $main-color;
  }

  #skills {
    height: 100vh;
    width: 100%;
    background: linear-gradient(240deg, #f5925d, #361c83);
  }

  #projects {
    height: 100vh;
    width: 100%;
    background: linear-gradient(230deg, #78139e, #2f0ba8);
  }

  #contacts {
    height: 100vh;
    width: 100%;
    background: linear-gradient(240deg, #5cddd9, #ee4bff);
  }

  ul {
    list-style-type: none;
  }

  div > img {
    width: 300px;
  }
</style>
