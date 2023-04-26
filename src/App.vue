<script>
import jumbo from './components/jumbo.vue'
export default {
  components: { jumbo },
  name: 'AppTitle',

  data() {
    return {
      title: 'La mia prima app con Vite!'    
    }
  }
}
</script>

<template>
  <h1>{{ title }}</h1>
  <jumbo/>
</template>

<style>
h1 {
  color: brown;
}
</style>
