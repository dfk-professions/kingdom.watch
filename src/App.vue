<template>
  <AppHeader/>
  <router-view/>
  <AppFooter/>
</template>

<script>
import AppHeader from "@/components/generic/AppHeader";
import AppFooter from "@/components/generic/AppFooter";

export default {
  name: 'App',
  components: {
    AppHeader,
    AppFooter
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>
