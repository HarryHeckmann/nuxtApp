<template>
  <section class="container">
    <Navbar/>
    <Showcase/>
      <About/>
      <Projects/>
      <Contact/>
  </section>
</template>

<script>
import Navbar from '~/components/Navbar.vue'
import Showcase from '~/components/Showcase.vue'
import About from '~/components/About.vue'
import Contact from '~/components/Contact.vue'
import Projects from '~/components/Projects.vue'

export default {
  components: {
    Navbar,
    Showcase,
    About,
    Contact,
    Projects
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

/* .title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
} */
</style>

