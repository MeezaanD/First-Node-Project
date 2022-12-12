<template>
  <body>
    <div class="home">
      <img class="img" src="../assets/cartoons.png">
      <HelloWorld msg="Welcome to Meezaan's Vue.Js App"/>
    </div>
  </body>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>

<style>
.home {
  padding-left: 20rem;
  padding-top: 5rem;
}
.img {
  width: 60rem;
  height: 30rem;
}


</style>