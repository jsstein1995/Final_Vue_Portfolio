<template>
  <div class="home">
    <Header/>
    <portfolio/>
  </div>
</template>

<script>
// @ is an alias to /src
import Portfolio from '@/components/Portfolio.vue'
import Header from '@/components/Header.vue'

export default {
  name: 'Home',
  components: {
    Header,
    Portfolio
  }
}
</script>
