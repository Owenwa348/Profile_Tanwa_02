<script setup>
import Porforlio from './components/PortfolioMe.vue';
import AboutMe from './components/AboutMe.vue';
import NavBarS from './views/NavBar.vue';
import ProjectsActivity from './components/ProjectsActivity.vue'
import SkillMe from './components/SkillMe.vue';
import ContactMe from './components/ContactMe.vue'

</script>

<template>
  <div>

     <div id="navbar">
      <NavBarS></NavBarS>
     </div>

    <div id="home">
      <Porforlio></Porforlio>
    </div>

    <div id="about">
      <AboutMe></AboutMe>
    </div>

    <div id="Projects & activity">
      <ProjectsActivity></ProjectsActivity>
    </div>

    <div id="Skill">
      <SkillMe></SkillMe>
    </div>

    <div id="ContactMe">
      <ContactMe></ContactMe>
    </div>

  </div>
</template>


