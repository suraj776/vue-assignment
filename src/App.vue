<template>
  <div id="app">
    <Header/>
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/header.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Header
  }
}

</script>


