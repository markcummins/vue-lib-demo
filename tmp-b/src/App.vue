<template>
  <HelloWorld msg="Welcome to Your Vue.js Appelication.."/>
</template>

<script>
// import HelloWorld from 'tmp'
import HelloWorld from '../../tmp/dist/tmp.umd.js' 

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>
