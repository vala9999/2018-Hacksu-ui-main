/* eslint-disable /
<template>
 <div id="maincontainer">

<div id="start-container">
  <div id="start-wrapper">
    <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/816158/hacksu-logo.svg" alt="Hacksu" title="Hacksu" id="hacksu-logo">
    <div id="start-text">
      <h1>Learn. Grow. Create.</h1>
      <h2 class="subtitle">Hacksu teaches anyone, regardless of skill level or major, how to code.</h2>
      <button v-scroll-to="{
     el: '#get-involved',
     duration: 500,
     easing: 'linear',
     offset: -100,
     cancelable: true,
     y: true}">Get Involved</button>
    </div>
  </div><!-- /Wrapper -->
</div><!-- /Container -->
<section>
  <div class="text-container">
    <h1>Who are we?</h1>
    <h2>My name is {{myName}} </h2>
    <input v-model="myName">
    <p>Hacksu is a student organization at Kent State University focused on learning and utilizing contemporary technologies. We are a very diverse community, spanning multiple majors from Fashion Design to Zoology and are open to students of any skill level. Everyone is welcome!</p>

    <div class= "member-container">
    <div v-for="name in names" class='member-icon'>
      <div class="member-name">
        {{name}}
      </div>

    </ul>
  </header>
  <div id="start-container">
    <div id="start-wrapper">
      <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/816158/hacksu-logo.svg" alt="Hacksu" title="Hacksu" id="hacksu-logo">
      <div id="start-text">
        <h1>Learn. Grow. Create.</h1>
        <h2 class="subtitle">Hacksu teaches anyone, regardless of skill level or major, how to code.</h2>
        <button>Get Involved</button>
      </div>
    </div><!-- /Wrapper -->
  </div><!-- /Container -->
  <section>
    <div class="text-container">
      <h1>Who are we?</h1>
      <h2>My name is {{myName}} </h2>
      <input v-model="myName">
      <p>Hacksu is a student organization at Kent State University focused on learning and utilizing contemporary technologies. We are a very diverse community, spanning multiple majors from Fashion Design to Zoology and are open to students of any skill level. Everyone is welcome!</p>

      <div class= "member-container">
        <div v-for="name in names" class='member-icon'>
          <div class="member-name">
            {{name}}
          </div>
        </div>
      </div>
      <div class="member-container">
        <div class="member-icon">
          <div class="member-name">Nolan</div>
          <img class="member-icon-image idle-icon" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7" data-src="https://lh3.googleusercontent.com/lpQE7yTChj9bdWKZCINKctuWs9Fd3RtzKOh0ffT27CgbDK2S5o7PM8hAjf4qpVsHS2UKdEnjXejHRT2lUACqgYO0SVbH5S1hPCkcXuswGDhBfWqJK1aNa0Lf6pbO-5mqfp3N7zinCWjKuGXInb_Ul0LSXGpMe9svifDrQUizLrnuUsMv6QS6ij-dRrL_9eWCSN0t-vqHMSlDudxAfEIayTyhbHAZ1eawZxCYwnTBNhh2F7XeW5BMmv4G2xOn0UP14BOsKeudw-TJTynMCUo1JLglIZ2Ii1_TBJFfApqLLq2J666OA0RYQrWLgUHRZbi6s6V8-hseiqDaK2aGFOlq1OpwqgYpbyMzhqBQ6Bn7hO1tY7YXl5hXPnJhytoIuWOSm--GrealyJxcIXRNLlKR5ZqZcMh5_ve9IEVF-adXyBU3LZyCXtIMaZowb41GFhro21XCDbgcIcA3MrytPKGQ6PGpQCelZtJMO-kkzgd03QArBstv_1q7TIGrgq70-3MSq32LvkKWjN1sJQNhkNC5iCe9TG8susgzLhFxMBdH6R7aVuz4Romu9liXWlu2SbDdACwPhHzk=w2000-h1694" />

          <img class="member-icon-image hover-icon" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7" data-src="https://lh3.googleusercontent.com/u-ICnoBlKl7HX44hMVskcldvOFm7V4F0trlALj9lUFnS3BSE-wZneZPkTbrVje65CyI8_9lUTA4_tUgOJm6D0ztGvxMDno3fCmRmd2PBrOCGLIXdoosAYFajrl7xZq33evS279vHlHB8jmVEUBmUG2Bq7_ICGEhSlQJHM2_MA4o99PyoAcVP4TSSLPHAT2DrzBKw2k9our976TAyTKERaRxPW8tGrfPAVR0Dx7w0Mod2aOFe0I5VOI29IYUaxeT8-2buw8Dr-QkokCp9hVKNJFYAWWoJjAFGsei8cSO_dvNOw9Q4-bZzEnDjuFuE1e5z511oZMEI0WHcIFFnRIDl4MVapRL4BfxsSEjSyj7L4P5SA4EC2bpxhMZCrb2ggYaVQDaFIXf8Q8dkaE-4RB9yhxnsVdnL1RcVQD6Vie-stWcw1mtZjKsD0R7BgCkUOc7HHlWQ_Kkm7pCEpge6nzeAwkLOiVIjxci-o8HpKGf4kFqz2fQvyCx-ui-4_h8TQQ19xYO0rUZFhhYd7HU2SRiUcrU3VCQPoVUuW9gMyYcGHmSQ3lL-6Z6eu1hNW_BkGtn3egnz1DeO=w2000-h1694" />

          <img class="member-icon-image active-icon" src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7" data-src="https://lh3.googleusercontent.com/UWNwFBJT_kaOhNWzSJaK2XyISktb-REMw_q9-ehB-vqzb6-Qgkp45ZZVFv435alrcW4sbbXrra5VB3QqP1HOmIJKqYApKSxqKUi7AXuDNJa1ftkd898DxXM29qKFSQqrJAVM1TpFrZ2HeR3qM4OUb6OOfMFOrDEFrmwbyYKYlHt1bMjvyguIELMY6ATnaNtOTGnPf3JTsXXEH3G9_1OJUD52qLypAyHES9b7bfAOoTN4GWqmK8HJ-tTqo4wm0hOU2KC3-BXCpUBZTb_aLr0WY__Pvz1QKJNYGWAk9Gclaxb98yL7mnWfYCVrNOr4tKO7X4u1c8Qx0MG3HaTI6WQ2N7I-gIdvfGmdhp6deSm0hsHmijg-XlqS0e6FAFUyCEesykvoTfIuuCh2z2N8xjeMjTDUGAR0lq2AfknHfnRhx0GWcOf80eldeDYH7AaUZi6RANV3RXSEfRrGuECjdpW6Lh9D939nwBNIgPhMR-AN5UmYXg3u9RBDF7vPuGFhhbSotfooAt75OuJzonMfLK4Sqkl-h-t-jdQXf1Ng5vBtJec7MuccTO-oh7w1W8dwRRnlj8-Jrok4=w2000-h1694" />

        </div>
      </div>
  </div>
</section>
<section class="green-section" id="meetings">
  <h1 class="text-container">Meetings</h1>
  <div class="text-container flex-row">
    <div class="half-container">
      <h2>Every Tuesday @ 7pm</h2>
      <h3>Honors College, room 060</h3>
      <p><a href="#" class="white-link">Need directions?</a></p>
    </div>
  </section>
  <section class="green-section" id="meetings">
    <h1 class="text-container">Meetings</h1>
    <div class="text-container flex-row">
      <div class="half-container">
        <h2>Every Tuesday @ 7pm</h2>
        <h3>Honors College, room 060</h3>
        <p><a href="#" class="white-link">Need directions?</a></p>
      </div>
      <div class="half-container flex-col">
        <ul class="meeting-list">
          <li>
            <div class="header">Web Basics, ExpressJS</div>
            <div class="content">
              <p>On the beginner side, we'll be learning the basics of web development - making websites! We will mostly be focusing on CSS and HTML. Make sure to bring a laptop! We will also be setting up Github accounts for those who don't have them.</p>
              <br>
              <p>On the advanced side, Isaac will be talking about Express.js, a Javascript framework for creating APIs!</p>

            </div>
          </li>
          <li>
            <div class="header">Web Basics, ExpressJS</div>
          </li>
          <li>
            <div class="header">Web Basics, ExpressJS</div>
          </li>
        </ul>
      </div>
    </div>
  </section>
  <section id="get-involved">
    <div class="text-container">
      <h1>Get Involved</h1>
      <p>The best way to stay informed is to join our <a href="https://www.facebook.com/groups/hacksu" target="_blank">Facebook Group</a> or sign up for our email list below. Also make sure to follow us on all the social media.</p>
      <br>
      <p>If you're interested in volunteering for Kent Hack Enough, you can join our <a href="https://khe.slack.com" target="_blank">Slack team.</a></p>
      <br><br>
      <label>Subscribe to email updates</label>
      <input type="email" placeholder="Email..."/>
      <button>Submit</button>
      <br>
    </div>

</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      myName: 'ben',
      names: ['elizabeth', 'alex', 'sami'],
    };
  },
  methods: {

  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
* {
  box-sizing: border-box;
}


#maincontainer {
    position:absolute;
    width:100%;
    left:0;
    top:0;
    padding-top:50px;
  background-color: #041017;
  font-family: 'Abel', sans-serif;

  color: white;
}

#start-container {
  min-height: 80vh;

  display: flex;
  flex-direction: column;
  justify-content: center;
}

    margin: 0 auto;
    box-shadow: 0 1px 0 0 rgba(0, 0, 0, 0.15);
    border-radius: 3px;

    background-color: #041017;
    color: white;
    opacity: 0;

    font-family: 'Abel', sans-serif;
    text-align: center;

    transition: none;

    box-sizing: border-box;

    z-index: 10;
  }

  .member-name:before {
   content: "";
   position: absolute;
   left: 50%;
   bottom: -10px;
   width: 12px;
   height: 12px;
   background-color: inherit;

   box-shadow: 0 1px 0 0 rgba(0, 0, 0, 0.15);
   transform: rotate(45deg) translateX(-50%);

   z-index: 99;
 }

 .member-icon:hover .member-name {
  width: 100%;
  padding: 10px 20px;
  opacity: 1;

  transition: width 0.2s ease-out, padding 0.2s ease-out;
}

header {
  display: flex;
  justify-content: flex-end;

  width: 100%;
  max-width: 1440px;
}

header li {
  display: inline-block;
  padding: 20px 20px;

  font-family: 'Abel', sans-serif;
}

a {

  text-decoration: none;

  /*transition: color 0.2s ease-out;*/
}

a:visited {

}

a:hover {

  text-decoration: underline;
}

.white-link:hover {
  text-decoration: underline;
  color: black;
}

button {
  width: auto;
  max-width: 300px;
  margin: 0.5em auto;
  padding: 12px 32px;
  border-radius: 2px;

  font-family: 'Ropa Sans', sans-serif;
  font-size: 16px;
  font-weight: 500;
  color: white;

  background: #35c982;

  box-shadow: none;
  border: none;

  cursor: pointer;

  transition: background-color 0.2s ease-out;
}

button:hover {
  background: #2DAF71;
}

h1, h2, h3, h4, .meeting-list .header, label {
  font-family: 'Ropa Sans', sans-serif;
}

h1 {
  font-size: 3em;
  line-height: 1.5em;
  margin-bottom: 0.5em;
}

h2 {
  font-size: 1.75em;
  line-height: 1.5em;
  font-weight: 300;
}

h3 {
  font-size: 1.5em;
  line-height: 1.375em;
}

.subtitle {
  font-family: 'Abel', sans-serif;
  color: #EAEAEA;

  line-height: 1.2em;
}

p {
  font-family: 'Abel', sans-serif;
  font-size: 1em;
  line-height: 1.2em;
}

label {
  display: block;

  width: 100%;
  line-height: 1em;
}

input[type=text], input[type=email], input[type=password] {

  width: 100%;
  max-width: 400px;
  padding: 8px 20px;

  margin: 0;
  margin-right: 4px;

  background: white;

  font-size: 1em;
}

footer {
  padding: 1em 0;
}

.social-icons {
  display: flex;
  justify-content: space-around;
  width: 100%;
  max-width: 500px;

  margin: 0 auto;
}

.social-icons svg {
  width: 50px;
  height: auto;
  fill: white;
}

@media screen and (max-width: 768px) {
  #start-container {
    justify-content: flex-start;
  }

  #start-wrapper {
    flex-wrap: wrap;
  }

  #hacksu-logo {
    width: 70%;
    margin: 10% auto 10%;
  }

  #start-text {
    width: 100%;
    margin: 0 auto;
    text-align: center;
  }

  #start-text button {
    width: 100%;
    margin-left: auto;
    margin-right: auto;
  }

  .green-section {
    text-align: center;
  }

  .half-container {
    width: 100%;
    margin-bottom: 1.5em;
  }

  p {
    font-size: 1em;
    line-height: 1.375em;
  }
}

@keyframes hop {
  30% {
    transform: translateY(-12px);
  }
  60% {
    transform: translateY(0px);
  }
  80% {
    transform: translateY(0px);
  }
  100% {
    transform: translateY(0px);
  }
}
</style>
