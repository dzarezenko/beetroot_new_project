<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <hello-world :msg="getTitle()"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorldComponent from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  data() {
    return {
      title: "Some title",
    }
  },
  components: {
    'hello-world': HelloWorldComponent // tag: component
  },
  methods: {
    getTitle() {
      return this.title + "!!!";
    },
  },
}
</script>
