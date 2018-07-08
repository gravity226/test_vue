<template>
  <div id="app">
    <h1>{{ title }}</h1>
    <Navbar />
  </div>
</template>

<script>
import Navbar from './Navbar'

export default {
  name: 'App',
  components: {
    Navbar
  },
  data () {
    return {
      title: 'my first vue app, woo!'
    }
  }
}
</script>

<style>
h1 {
  color: #444;
  font-weight: normal;
  text-align: center;
}
</style>
