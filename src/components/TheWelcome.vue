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
    <h3>
    Projects are found here at my Knockout.js portfolio:
    <a href="https://turtle-head.github.io/Portfolio/" target="_blank" rel="noopener">portfolio grid</a>
    and you can find the source code as well as the live site for each project.</h3>
    <br>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Skills</template>
<h3 class="green">Education is important to me, I regularly take courses to improve my skills.</h3>
<br>
<h3>If my code interests you feeel free to look at</h3> <a href="https://github.com/Turtle-head" target="_blank" rel="noopener">my GitHub repositories.</a>
    <br />


  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact</template>

    <a href="mailto:fehr.james@gmail.com">Email me </a>
    <br>
  </WelcomeItem>



  </template>
