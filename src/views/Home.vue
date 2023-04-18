<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Search></Search>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Search from './Search.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Search
  },
  methods: {
    test () {
      const a = 1111
      console.log(a)
      console.log(111111111111111)
    }
  }
}
</script>
