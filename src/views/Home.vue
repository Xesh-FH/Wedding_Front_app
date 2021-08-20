<template>
  <div class="home">
    <img alt="" src="#">
    <HelloWorld msg="Bienvenue sur le livre d'Or"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>
  img {
    background: transparent;
  }
</style>
