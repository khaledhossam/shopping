<template>
  <div class="home">
    <nav-bar></nav-bar>
  </div>
</template>

<script>
// @ is an alias to /src
import NavBar from '@/components/NavBar.vue'

export default {
  name: 'NavBar',
  components: {
    "nav-bar":NavBar
  }
}
</script>
