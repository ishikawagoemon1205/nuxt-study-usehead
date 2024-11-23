<script setup lang="ts">
useHead({
  title: 'テスト:テストページ',
  meta: [
    { name: 'fwefrfr', content: 'Nuxt 3' }
  ]
})

</script>

<template>
    <h2 @click="navigateTo('/')">テストページ</h2>
</template>