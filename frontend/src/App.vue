<script setup>
import OpenBrowser from './components/OpenBrowser.vue'
import HelloWorld from './components/HelloWorld.vue'</script>

<template>
  <img id="logo" alt="Wails logo" src="./assets/images/logo-universal.png"/>
  <HelloWorld/>
  <img id="logo" alt="Wails logo" src="./assets/images/img.png"/>
  <OpenBrowser/>
</template>


<style>
#logo {
  display: block;
  width: 50%;
  height: 50%;
  margin: auto;
  padding: 10% 0 0;
  background-position: center;
  background-repeat: no-repeat;
  background-size: 100% 100%;
  background-origin: content-box;
}
</style>
