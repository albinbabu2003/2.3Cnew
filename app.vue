<template>
  <div id="app">
    <!-- Your application content goes here -->
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
/* Global styles for the entire application */

#app {
  font-family: Arial, sans-serif;
  background-color: #f0f0f0;
  margin: 0;
  padding: 0;
  min-height: 100vh; /* Ensure the app takes at least the full viewport height */
}
</style>
