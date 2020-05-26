<template>
  <div class="about">
    <Resume/>
  </div>
</template>

<script>
// @ is an alias to /src
import Resume from '@/components/Resume.vue'

export default {
  name: 'About',
  components: {
    Resume
  }
}
</script>