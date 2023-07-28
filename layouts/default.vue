<script setup>
useHead({
  htmlAttrs: {
    lang: 'en',
  },
  meta: [
    { property: 'og:title', content: `Analyze-KE` },
    { name: 'description', content: 'Analyze-KE is a Task Management Dashboard built with Nuxt 3 and TailwindCSS.' },
    { property: 'og:description', content: 'Analyze-KE is a Task Management Dashboard built with Nuxt 3 and TailwindCSS.' },
    { property: 'og:url', content: 'https://hounter-ke.vercel.app/' },
    { name: 'twitter:title', content: 'Hounter - House Hunter' },
    { name: 'twitter:description', content: 'Analyze-KE is a Task Management Dashboard built with Nuxt 3 and TailwindCSS.' },
    { name: 'twitter:site', content: 'https://hounter-ke.vercel.app/' }
  ],
  title: `Hounter - House Hunter`,
})
</script>

<template>
  <main class="max-w-9xl font-fontFamily">
    <slot/>
  </main>
</template>
