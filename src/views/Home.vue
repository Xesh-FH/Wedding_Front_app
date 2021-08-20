<template>
  <div class="home">
    <div class="up">
        <img alt="" src="#">
        <HelloWorld msg="Bienvenue sur le livre d'Or"/>
    </div>
    <div class="parallax">
    </div>
    <div class="down">
      Crédits
    </div>
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
  .parallax
  {
    background-image:url("../assets/E&F.jpg");
    height:500px;
    background-attachment:fixed;
    background-position:center;
    background-repeat:no-repeat;
    background-size:cover;
  }

  .up, .down
  {
    height: 500px;
  }
</style>
