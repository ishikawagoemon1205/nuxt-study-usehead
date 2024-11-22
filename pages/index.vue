<script setup lang="ts">

useHead({
  title: 'テスト：ルート',
  meta: [
    { name: 'fwefrfr', content: 'Nuxt 3' }
  ]
})

</script>

<template>
  <div>
    <h1 @click="navigateTo('/home')">ルート</h1>
    grgtrgt
  </div>
</template>