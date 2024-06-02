<template>
  <NewHeader />
  <MyHome />
  <AboutMe />
  <MySkills />
  <MyProjects />
  <ContactMe/>
</template>

<script>
import NewHeader from './components/Header.vue'
import MyHome from './components/Home.vue'
import AboutMe from './components/About.vue'
import MySkills from './components/Skills.vue'
import MyProjects from './components/Projects.vue'
import ContactMe from './components/Contact.vue'

export default {
  name: 'App',
  components: {
    NewHeader, MyHome, AboutMe, MySkills, MyProjects, ContactMe
  }
}
</script>

<style lang="scss">
@import url('./scss/main.scss'); 

</style>
