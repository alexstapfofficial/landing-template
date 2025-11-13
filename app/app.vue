<script setup lang="ts">
useHead({
  meta: [
    { name: 'viewport', content: 'width=device-width, initial-scale=1' },
  ],
  link: [
    { rel: 'icon', href: '/favicon.ico' }
  ],
  htmlAttrs: {
    class: '',
    lang: 'de'
  },
  script: [
    { src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }
  ]
})
</script>

<template>
  <UApp :toaster="{ expand: false }">
    <UMain class="relative">
      <NuxtPage />
    </UMain>
  </UApp>
</template>