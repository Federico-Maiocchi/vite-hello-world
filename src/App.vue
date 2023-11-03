<script>
import AppHero from './components/AppHero.vue'
export default {
  data() {
    return {
      message: 'La mia prima app con Vite!'
    }
  },

  components: {
    AppHero
  },

  methods: {
    
  }
}
</script>

<template>
  <h1 class="messaggio">{{ message }}</h1>
    <AppHero/>
  
</template>

<style scoped>
.messaggio {
  color: red;
  text-align: center;
}
</style>
