<script setup lang="ts">

useHead({
  title: 'テスト：Home',
  meta: [
    { name: 'fwefrfr', content: 'Nuxt 3' }
  ]
})

</script>


<template>
  <div>
    <h1 @click="navigateTo('/')">ルート</h1>
    
  </div>
</template>