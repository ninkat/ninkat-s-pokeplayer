<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Purpose</template>
    The purpose of this prgram is to create better study habits!
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>How does this program work?</template>
    Create better habits by logging your hours studied using the logs feature.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Sources</template>
    Getting started with BootstrapVue
    <br><a href="https://blog.logrocket.com/getting-started-bootstrapvue/">Click Here</a>
    <br>
    <br>Font Tags
    <br><a href="https://www.w3schools.com/tags/tag_font.asp">Click Here</a>
    <br>
    <br>CSS Background-Color Property
    <br><a href="https://www.w3schools.com/cssref/pr_background-color.php">Click Here</a>
    <br>
    <br>How to Add & Change Background Color in HTML
    <br><a href="https://blog.hubspot.com/website/change-background-color-html">Click Here</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Contributors</template>
    Dion Barja
    <br>Timmy Wang
    <br>Caleb Pollreis
  </WelcomeItem>
</template>
