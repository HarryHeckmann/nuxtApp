<template>
  <section class="container">
    <Navbar/>
    <Showcase/>
  </section>
</template>

<script>
import Navbar from '~/components/Navbar.vue'
import Showcase from '~/components/Showcase.vue'

export default {
  components: {
    Navbar,
    Showcase
  }
}
</script>

