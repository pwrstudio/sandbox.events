<template>
  <div class="home">
    <div>
      <p>Some text...</p>
    </div>
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

<style lang="scss">
.home {
  margin-right: 20px;
  margin-left: 20px;
  color: white;
  word-spacing: -0.2em;
}
</style>
