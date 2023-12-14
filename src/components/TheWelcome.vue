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
<h3>I am always working to increase my skills in how to use a variety of skills.</h3>
<br>
    <ul><li>HTML5,HTML 7+ yrs</li>
    <li>JavaScript 7+ yrs</li>
    <li>jQuery  7+ yrs</li>
    <li>Knockout 7+ yrs</li>
    <li>Bootstrap 7+ yrs</li>
    <li>Gulp 7+ yrs</li>
    <li>React 1+ yrs</li>
    <li>Next 1+ yrs</li>
    <li>Angular 1+ yrs</li>
    <li>Python 1+ yrs</li>
    <li>C# 1+ yrs</li>
    <li>C++ 1+ yrs</li>
    <li>C 10+ yrs</li>
    <li>Visual Basic 2+ yrs</li>
</ul>

    <br>If my code interests you feeel free to look at <a href="https://github.com/Turtle-head" target="_blank" rel="noopener">my GitHub repositories.</a>
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
