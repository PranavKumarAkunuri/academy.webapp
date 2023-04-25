<template>
  <div class="home">
    <NavBar/>
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome To SS ACADEMY"/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HelloWorld from '@/components/HelloWorld.vue' // @ is an alias to /src
import NavBar from '@/components/NavBar.vue'

export default defineComponent({
  name: 'HomeView',
  components: {
    HelloWorld,
    NavBar
  }
})
</script>
