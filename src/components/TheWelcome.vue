<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
</script>

<template>
    <WelcomeItem>
      <template #icon>
        <DocumentationIcon />
      </template>
      <template #heading>Articles</template>

      Text's produced mostly for self learning, and providing hiring managers an idea of my knowledge.
    </WelcomeItem>
    <WelcomeItem>
      <template #icon>
        <ToolingIcon />
      </template>
      <template #heading>Resources</template>

      Some programs, proof-of-concepts, guides, and software I made along my journey.
    </WelcomeItem>
</template>
