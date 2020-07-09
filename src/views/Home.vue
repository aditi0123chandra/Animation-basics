<template>
  <div class="home">
    <AboutUs/>
    <Learnshala/>
  </div>
</template>

<script>
// @ is an alias to /src
import AboutUs from '@/components/AboutUs.vue'
import Learnshala from '@/components/Learnshala.vue'

export default {
  name: 'Home',
  components: {
    AboutUs,
    Learnshala
  }
}
</script>
