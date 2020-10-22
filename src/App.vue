<template>
  <div id="app">
    <div id="nav">
      <Navigation></Navigation>
    </div>
    <router-view />
  </div>
</template>

<script>
import Navigation from '@/components/Navigation';

export default {
    name: 'App',
    components: {
        Navigation
    }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  background-color: #EDD2A4;
  padding-bottom: 30px;
}
</style>