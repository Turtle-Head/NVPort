<script setup>
import WelcomeItem from './WelcomeItem.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Projects</template>

    Projects are found here at my Knockout.js portfolio:
    <a href="https://turtle-head.github.io/Portfolio/" target="_blank" rel="noopener">portfolio grid</a>
    and you can find the source code as well as the live site for each project.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Skills</template>

    My skills list along with my experience level for each skill can be found here on my HTML and CSS portfolio:
    <a href="https://turtle-head.github.io/PortfolioDeux/" target="_blank" rel="noopener">Skills page</a>.<br>

    <br>If my code interests you feeel free to look at <a href="https://github.com/Turtle-head" target="_blank" rel="noopener">my GitHub repositories.</a>
    <br />


  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact Me</template>

    <a href="mailto:fehr.james@gmail.com">Contact Me</a> <br>
    <!-- <a href="https://www.linkedin.com/in/fehrjames/" target="_blank" rel="noopener">LinkedIn profile</a><br> -->
  </WelcomeItem>
  


  </template>
