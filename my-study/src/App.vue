<template>
  <div id="app">
    <app-header></app-header>
    <br>
    <router-view/>
  </div>
</template>

<script>
import header from "./components/header"
export default {
  name: 'App',
  components: {
    appHeader : header
  }
}
</script>

<style>
</style>
