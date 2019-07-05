<template>
  <div id="app">
    <Navbar />
    <ParallaxContainer id="index-banner" imgSrc="images/background1.jpg" imgAlt="Some cool picture of a motorbike">
        <br><br>
        <h1 class="header center teal-text text-lighten-2">Parallax Template</h1>
        <div class="row center">
          <h5 class="header col s12 light">A modern responsive front-end framework based on Material Design</h5>
        </div>
        <div class="row center">
          <a href="http://materializecss.com/getting-started.html" id="download-button" class="btn-large waves-effect waves-light teal lighten-1">Get Started</a>
        </div>
        <br><br>
    </ParallaxContainer>
    <Section>
      <!--   Icon Section   -->
      <div class="row">
        <div class="col s12 m4">
          <div class="icon-block">
            <h2 class="center brown-text"><i class="material-icons">flash_on</i></h2>
            <h5 class="center">Speeds up development</h5>

            <p class="light">We did most of the heavy lifting for you to provide a default stylings that incorporate our custom components. Additionally, we refined animations and transitions to provide a smoother experience for developers.</p>
          </div>
        </div>

        <div class="col s12 m4">
          <div class="icon-block">
            <h2 class="center brown-text"><i class="material-icons">group</i></h2>
            <h5 class="center">User Experience Focused</h5>

            <p class="light">By utilizing elements and principles of Material Design, we were able to create a framework that incorporates components and animations that provide more feedback to users. Additionally, a single underlying responsive system across all platforms allow for a more unified user experience.</p>
          </div>
        </div>

        <div class="col s12 m4">
          <div class="icon-block">
            <h2 class="center brown-text"><i class="material-icons">settings</i></h2>
            <h5 class="center">Easy to work with</h5>

            <p class="light">We have provided detailed documentation as well as specific code examples to help new users get started. We are also always open to feedback and can answer any questions a user may have about Materialize.</p>
          </div>
        </div>
      </div>
    </Section>
    <ParallaxContainer imgSrc="images/background2.jpg" imgAlt="Unplashed background img 2">
      <div class="row center">
          <h5 class="header col s12 light">A modern responsive front-end framework based on Material Design</h5>
      </div>
    </ParallaxContainer>
    
    <Section>
      <div class="row">
        <div class="col s12 center">
          <h3><i class="mdi-content-send brown-text"></i></h3>
          <h4>Contact Us</h4>
          <p class="left-align light">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam scelerisque id nunc nec volutpat. Etiam pellentesque tristique arcu, non consequat magna fermentum ac. Cras ut ultricies eros. Maecenas eros justo, ullamcorper a sapien id, viverra ultrices eros. Morbi sem neque, posuere et pretium eget, bibendum sollicitudin lacus. Aliquam eleifend sollicitudin diam, eu mattis nisl maximus sed. Nulla imperdiet semper molestie. Morbi massa odio, condimentum sed ipsum ac, gravida ultrices erat. Nullam eget dignissim mauris, non tristique erat. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae;</p>
        </div>
      </div>
    </Section>

    <ParallaxContainer imgSrc="images/background3.jpg" imgAlt="Unsplashed Background image 3">
      <div class="row center">
        <h5 class="header col s12 light">A modern responsive front-end framework based on Material Design</h5>
      </div>
    </ParallaxContainer>

    <Footer>
      <template v-slot:main>
        <div class="row">
          <div class="col l6 s12">
            <h5 class="white-text">Company Bio</h5>
            <p class="grey-text text-lighten-4">We are a team of college students working on this project like it's our full time job. Any amount would help support and continue development on this project and is greatly appreciated.</p>

          </div>
          <div class="col l3 s12">
            <h5 class="white-text">Settings</h5>
            <ul>
              <li><a class="white-text" href="#!">Link 1</a></li>
              <li><a class="white-text" href="#!">Link 2</a></li>
              <li><a class="white-text" href="#!">Link 3</a></li>
              <li><a class="white-text" href="#!">Link 4</a></li>
            </ul>
          </div>
          <div class="col l3 s12">
            <h5 class="white-text">Connect</h5>
            <ul>
              <li><a class="white-text" href="#!">Link 1</a></li>
              <li><a class="white-text" href="#!">Link 2</a></li>
              <li><a class="white-text" href="#!">Link 3</a></li>
              <li><a class="white-text" href="#!">Link 4</a></li>
            </ul>
          </div>
        </div>
      </template>

      <template v-slot:copyright>
        Made  asdfa by <a class="brown-text text-lighten-3" href="http://materializecss.com">Materialize</a>
      </template>
    </Footer>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import ParallaxContainer from "./components/ParallaxContainer"
import Section from "./components/Section"
import Footer from "./components/Footer"

export default {
  name: 'app',
  components: {
    Navbar,
    ParallaxContainer,
    Section,
    Footer,
  }
}
</script>

<style>

</style>
