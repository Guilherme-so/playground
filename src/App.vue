<script setup>
import Playground from "./components/playground.vue";
</script>

<template>
  <Playground />
</template>

<style>
html {
  box-sizing: border-box;
  width: 100%;
  height: 100%;
}

*,
*:before,
*:after {
  box-sizing: inherit;
  padding: 0;
  margin: 0;
}
body {
  font-family: sans-serif;
  height: 100%;
  margin: 0;
  background: #261c33;
  overflow: hidden;
  display: flex;
  align-items: center;
  justify-content: center;
}

h2 {
  color: #8d81f3;
  text-align: center;
  font-size: 40px;
  margin: 20px;
}
</style>
