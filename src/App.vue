<template>
  <div>
    <Heading/>
    <Skills/>
    <Experience/>
    <Projects/>
    <ContactMe/>
  </div>
</template>

<script>
import Heading from './components/Heading.vue'
import Skills from './components/Skills.vue'
import Projects from './components/Projects.vue'
import Experience from './components/Experience.vue'
import ContactMe from './components/ContactMe.vue'

export default {
  components : {
    Heading, 
    Skills,
    Projects,
    Experience,
    ContactMe
  }
  
}
</script>

<style>
  body {
    margin : 0px ; 
  }

</style>
