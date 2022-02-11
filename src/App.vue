<script setup lang="ts">
// https://github.com/vueuse/head
// you can use this to manipulate the document head in any components,
// they will be rendered correctly in the html results with vite-ssg
useHead({
  title: 'J Parker',
  meta: [
    { name: 'description', content: 'Opinionated Vite Starter Template' },
  ],
})
</script>

<template>
  <router-view />
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Comforter&family=Play:wght@700&family=Rowdies&display=swap');
#app {
  font-family: 'play', sans-serif;
}
:root {
--pink: #F72585;
--byza: #B5179E;
--purp: #7209B7;
--main: #3A0CA3;
--main2: #3F37C9;
--main3: #4361EE;
--main4: #4895EF;
--lite: #4CC9F0;
}
</style>
