<template>
  <div class="home">
    <img src="../assets/giskonsult-logo.png">
    <HelloWorld msg="GISkonsult plc website under develoment"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
