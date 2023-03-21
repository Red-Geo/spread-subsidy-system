<script setup>
  const route = useRoute()
  console.log(route)
</script>

<template>
  <div>
    <h1>動態頁面 {{route.path}}</h1>
  </div>
</template>

<style>

</style>