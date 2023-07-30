<script setup>
useHead({
  htmlAttrs: {
    lang: 'en',
  },
  meta: [
    { property: 'og:title', content: `Analyze-KE - Task Management Dashboard` },
    { name: 'description', content: 'Analyze-KE is a Task Management Dashboard built with Nuxt 3 and TailwindCSS.' },
    { property: 'og:description', content: 'Analyze-KE is a Task Management Dashboard built with Nuxt 3 and TailwindCSS.' },
    { property: 'og:url', content: 'https://analyze-ke.vercel.app/' },
    { name: 'twitter:title', content: 'Analyze-KE - Task Management Dashboard' },
    { name: 'twitter:description', content: 'Analyze-KE is a Task Management Dashboard built with Nuxt 3 and TailwindCSS.' },
    { name: 'twitter:site', content: 'https://analyze-ke.vercel.app/' }
  ],
  title: `Analyze-KE - Task Management Dashboard`,
})
</script>

<template>
  <main class="max-w-9xl font-fontFamily flex">
    <Sidebar />
    <div class="w-full">
      <slot/>
    </div>
  </main>
</template>
