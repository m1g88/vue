<template>  
  <div>
    App components
    <br>
    <router-link to="/">Home</router-link>
    <br>
    <router-link to="/about">About</router-link>
    <br>
    <router-view></router-view>
  </div>
</template>

<script>
export default {

}
</script>
<style>
  @import '../node_modules/semantic-ui-css/semantic.min.css';
</style>