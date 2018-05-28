<template>
  <parallax>
    <div class="intro-body">
      <a href="" class="intro-logo"><img src="../assets/logo.png" alt=""></a>
      <div id="photo">
        <img src="../assets/photo/tony.jpg" alt="">
      </div>
      <div id="name">
        <h1>Robert Downey Jr.</h1>
      </div>
      <div id="passion">
        <h2>FRONT-END WEB DEVELOPER</h2>
      </div>
      <div id="about">
        <ul>
          <li>I like to code because I really enjoy building things (from "lego" to chair to websites and JS-apps)</li>
          <li>And I like to be able to take an idea and make it happen on the screen</li>
          <li>Coding is my passion because coding is the way of the future</li>
          <li>And I try to make this world a better place</li>
          <li>And may I tell you a secret? I have a dream to get a job with a good pay )))</li>
        </ul>
      </div>
    </div>
  </parallax>
</template>

<script>
  export default {
    name: 'it Intro',
  }
</script>

<style lang="scss" scoped>
  @import '../styles/variables';
  * {
    color: $main-color;
  }

  .intro-body {
    height: 100vh;
    width: 100%;
    background: linear-gradient(180deg, #bc00ff, #4c0fcc);
    background-size: 300% 300%;
    animation: introGradient 8s ease infinite;
    -webkit-animation: introGradient 8s ease infinite;
    -moz-animation: introGradient 8s ease infinite;
  }

  @keyframes introGradient {
    0% {
      background-position: 87% 0%
    }
    50% {
      background-position: 14% 100%
    }
    100% {
      background-position: 87% 0%
    }
  }

  .intro-logo {
    margin-top: 50px;
    position: fixed;
    box-sizing: border-box;
    z-index: 999;
    img {
      width: 50px;
      background: transparent;
    }
  }

  #photo > img {
    width: 200px;
  }

  #about > ul {
    list-style-type: none;
  }
</style>
