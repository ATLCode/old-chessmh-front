<template>
  <TopBar />
  <router-view />
</template>

<script setup>
import TopBar from "@/components/TopBar";
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  padding: 0;
  margin: 0;
}

body {
  padding: 0;
  margin: 0;
}
</style>
