<template>
  <div>{{ a }}</div>
  <div>{{ obj.age }}</div>
  <Child />
  <One />
</template>

<script setup>
let a = ref('Hello word')
let obj = reactive({
  name: 'zhangsan',
  age: 18
})
console.log(a.value)
console.log(obj.name)
</script>

<style>
</style>