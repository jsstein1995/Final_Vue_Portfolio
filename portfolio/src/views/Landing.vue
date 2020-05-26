<template>
  <div class="landing">
    <LandComp/>
  </div>
</template>

<script>
// @ is an alias to /src
import LandComp from '@/components/LandComp.vue'

export default {
  name: 'landing',
  components: {
    LandComp
  }
}
</script>