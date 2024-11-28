<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import CrownIcon from './icons/IconCrown.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem link="https://oi.reqwey.me">
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>My Blog</template>

    Some random notes. Not only for OI contests.
  </WelcomeItem>

  <WelcomeItem link="#">
    <template #icon>
      <CrownIcon />
    </template>
    <template #heading>Gennia (Deprecated)</template>

    Yet another quick strategy online game. Protect your land and capture other's general! The GenniaBot is also awesome.
    Come and join <a href="https://github.com/GenniaApp" target="_blank" rel="noopener">GenniaApp</a> open-source developing team now!
  </WelcomeItem>

  <WelcomeItem link="https://chemicalc.reqwey.me">
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Chemistry Calculator</template>

    A small tool to analyze the quantity number of complex chemicals. Powered by React.
  </WelcomeItem>

  <WelcomeItem link="https://t.me/yReqwey">
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Contact</template>

    Chat with me(@yReqwey) via Telegram!
  </WelcomeItem>
</template>
