<template>
  <div id="app">
    <navigatin></navigatin>
    <router-view/>
    <foot></foot>
  </div>
</template>

<style>

</style>
<script>
  import Nav from "./components/nav";
  import Footer from "./components/footer";
  export default {
    components: {
      'foot' : Footer,
      'navigatin' : Nav
    }
  }
</script>