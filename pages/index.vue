<script setup>
  const point = ref(100)
  onMounted(()=>{
    setInterval(() => {
      point.value++;
    }, 1000);
  })

  const {count} = useAddCount()
  console.log(count)
</script>

<template>
  <div>
    <h1>首頁</h1>
    <h1>{{point}}</h1>
    <h2>{{count}}</h2>
    <Card />
    <Todo />
  </div>
</template>

<style>

</style>