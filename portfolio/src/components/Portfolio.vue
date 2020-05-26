<template>
  <div ref="scrollSections">
    <section class="landing-section" data-scroll-section>
      <div class="rocks-container">
          <img class="rocks-image" src="../assets/img/front-rocks.png" alt="top_image">
      </div>
      <section data-scroll-section>
        <div class="top-color-1" data-scroll data-scroll-speed=".05"></div>
      </section>

      <div class="job-title-container">
                <div v-if='topTextDisplay' class="line1 sliding">
                    <div class="letterContainer jobTitle"
                    v-for='(letter, index) in line1Letters' :key="index">
                        <span class="port">{{letter}}</span>
                        <div class="TextBox" ></div>
                    </div>
                </div>
                <div v-if='topTextDisplay' class="line2">
                    <div class="letterContainer jobTitle"
                    v-for='(letter, index) in line2Letters' :key="index">
                        <span class="port">{{letter}}</span>
                        <div class="TextBox" ></div>
                    </div>
                </div>
                <div v-if='topTextDisplay' class="line3">
                    <div class="letterContainer jobTitle"
                    v-for='(letter, index) in line3Letters' :key="index">
                        <span class="port">{{letter}}</span>
                        <div class="TextBox" ></div>
                    </div>
                </div>
                <div v-if='topTextDisplay' class="line4">
                    <div class="letterContainer jobTitle"
                    v-for='(letter, index) in line4Letters' :key="index">
                        <span class="port">{{letter}}</span>
                        <div class="TextBox" ></div>
                    </div>
                </div>
                <div v-if='topTextDisplay' class="line5">
                    <div class="letterContainer jobTitle"
                    v-for='(letter, index) in line5Letters' :key="index">
                        <span class="port">{{letter}}</span>
                        <div class="TextBox" ></div>
                    </div>
                </div>
            </div>
    </section>
    <section class="top-color-2" data-scroll-section></section>

    <section class="long-bio" data-scroll-section>
        <p>Hi, I’m Jackson. I love</p>
        <p>designing</p>
        <p>and coding</p>
        <p>user interfaces in </p>
        <p>Javascript.</p>
    </section>

    <section class="big-numbers" data-scroll-section>
      <div class="number-group"
          v-for='(years, index) in yearGroups' :key="index">
          <div class="years">{{years.number}}</div>
          <div class="years-description">{{years.title}}</div>
      </div>
    </section>
    <section class='career-section-container' data-scroll-section>
      <span class="big-text">
          <div class="career-section-title-small" data-scroll data-scroll-speed="2" data-scroll-direction="horizontal">Career History</div>
      </span>
      <div class="position">
        <div class="position-years">
            2019-2020
        </div>
        <div class="position-title">
            FE Developer / UI Designer  <br> at &nbsp;
          <div class="cb-Link">
            <a class="cb-fancy-link" href="https://www.callbox.com/" target="blank">Call Box</a>
            <div class="company-logo-container">
                <a href="https://www.callbox.com/" target="blank">
                    <img id="callbox-logo" class="callbox-logo" src="../assets/img/callbox@3x-1.png" alt="callbox-logo">
                </a>
            </div>
          </div>
        </div>
        <p class="position-description">
            Front-End Developer and UI Designer, updating their UI and building fresh new components 
            for their web and mobile texting platform in an Agile development environment.
        </p>
      </div>
    </section>
    <section class="callbox-web" data-scroll-section>
        <span class="big-text">
            <div class="cb-projects-title">Call Box Projects</div>
        </span>
    </section>

    <section class="cb-wheel-section" data-scroll-section>
      <div class="cb-websites-info-section">
        <div class="cb-websites-info-title">
            SaaS Platform Projects
        </div>
        <div class="cb-websites-info">
            Front-End Developer and UI Designer, updating their UI and building 
            fresh new components for their web and mobile texting platform 
            in an Agile development environment.
        </div>
      </div>     
      <img alt="mockups" src="../assets/img/mxyou.png">           
    </section>      



    <h1>{{ msg }}</h1>
    <section data-scroll-section>
      <h3 data-scroll data-scroll-speed="1">Installed CLI Plugins</h3>
      <ul data-scroll data-scroll-speed="2">
        <li>
          <a
            href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel"
            target="_blank"
            rel="noopener"
          >babel</a>
        </li>
        <li>
          <a
            href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint"
            target="_blank"
            rel="noopener"
          >eslint</a>
        </li>
      </ul>
    </section>
    <section data-scroll-section>
      <h3 data-scroll data-scroll-speed="1">Essential Links</h3>
      <ul data-scroll data-scroll-speed="2">
        <li>
          <a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a>
        </li>
        <li>
          <a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a>
        </li>
        <li>
          <a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a>
        </li>
        <li>
          <a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a>
        </li>
        <li>
          <a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a>
        </li>
      </ul>
    </section>
    <section data-scroll-section>
      <h3 data-scroll data-scroll-speed="4">Ecosystem</h3>
      <ul data-scroll data-scroll-speed="2">
        <li>
          <a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a>
        </li>
        <li>
          <a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a>
        </li>
        <li>
          <a
            href="https://github.com/vuejs/vue-devtools#vue-devtools"
            target="_blank"
            rel="noopener"
          >vue-devtools</a>
        </li>
        <li>
          <a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a>
        </li>
        <li>
          <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a>
        </li>
      </ul>
    </section>
  </div>
</template>

<script>
import locomotiveScroll from "locomotive-scroll";
import $ from 'jquery'

export default {
  name: "locoScroll",
  props: {
    msg: String
  },
  data() {
    return {
      scrollIns: null,
      name: 'Jackson.Stein',
      bio: 'Front-End.Developer.UI-Designer.Creative.VUE-Developer.Coder.Web-Designer',
      letters: [],
      bioLetters: [],
      displayText: false,
    //   topText: {
    //     line1: 'UX.D',
    //     line2: 'EV',
    //     line3: 'ELEOPER',
    //     line4: '/UI.',
    //     line5: 'DES',
    //     line6: 'IGNER'
    //   },
      line1: 'FRONT-',
      line2: 'END',
      line3: 'DEVELOPER',
      line4: '/UI',
      line5: 'DESIGNER',
    //   line6: 'IGNER',
      topTextDisplay: true,
      line1Letters: [],
      line2Letters: [],
      line3Letters: [],
      line4Letters: [],
      line5Letters: [],
    //   line6Letters: [],
      yearGroups: [
        {
            number: '01',
            title: 'Developing Positions'
        },
        {
            number: '02',
            title: 'Years Developing'
        },
        {
            number: '03',
            title: 'Years of Freelance Design'
        },
        {
            number: '25',
            title: 'Years Lived'
        }
      ]
    };
  },
  mounted() {
    const _self = this;
    this.$nextTick(function() {
      _self.initLocoScroll();
    });
    this.splitLines();
    this.loadLanding();
    // this.loadRainbow();
  },
  methods: {
    initLocoScroll() {
      const _self = this;
      this.scroll = new locomotiveScroll({
        el: _self.$refs['scrollSections'],
        smooth: true,
        smoothMobile: true,
        getDirection: true,
        initClass: true
      });
    },
    splitBio: function () {
      var text = this.bio.toUpperCase().split('');
      this.bioLetters = text;
    },
    splitLines: function () {
        var text1 = this.line1.split('');
        var text2 = this.line2.split('');
        var text3 = this.line3.split('');
        var text4 = this.line4.split('');
        var text5 = this.line5.split('');
      //   var text6 = this.line6.split('');
        this.line1Letters = text1
        this.line2Letters = text2
        this.line3Letters = text3
        this.line4Letters = text4
        this.line5Letters = text5
      //   this.line6Letters = text6
      },
      loadLanding: function () {
          //image & jobTitle fade in
          var elements = ['nav-links-top','rocks-image','job-title-container'];

          for (let i = 0; i < elements.length; i++) {
              var thisElement = $("." + elements[i]); //Get the current element based on class
              fadeInElement(thisElement, i);          //Call our "Fade in" function
          }
          function fadeInElement(elem, time) {      //Fade-in function that takes the element to fade-in, and the time it should wait
              setTimeout(function() {
                  elem.css('opacity', 1);
              }, 1650 * time + 500);                        //Set the time it should wait
          }
      },
      // loadRainbow: function () {
      //     var rainbow = $(".rainbow");
      //     setTimeout(function() { rainbow.style.opacity = .95 }, 3000); 
      // }
  }
};

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a {
  color: #42b983;
}
.big-text{
  margin-right: -40rem;
}
</style>
