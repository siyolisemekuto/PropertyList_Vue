<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/table-mountain.jpg">
    <HelloWorld msg="Cape Town Property Listings"/>
  </div>
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
<style scoped>
img{
  object-fit: cover;
  opacity:0.7;
}
</style>