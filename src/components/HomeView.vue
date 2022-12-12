<template>
  <body>
    <div class="home">
      <img class="img img-fluid" src="../assets/cartoons.png">
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
  padding: 5rem;
}

.img {
  width: 100%;
  height: 30rem;
}
body {
  width: 100%;
}


</style>