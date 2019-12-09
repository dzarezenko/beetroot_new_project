<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <hello-world msg="HELLO WORLD!"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorldComponent from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    'hello-world': HelloWorldComponent // tag: component
  }
}
</script>
