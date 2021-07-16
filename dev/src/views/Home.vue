<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

let fs = require('fs')
console.log(fs.readFile)

export default {
    name: 'Home',
    components: {
        HelloWorld
    },
    mounted(){
        let path = require('path')
        console.log(path.resolve)

    }
}
</script>
