<template>
  <div class="about">
    <h1>Developers</h1>
    <DeveloperProfile/>
  </div>
</template>

<script>
import DeveloperProfile from '@/components/DeveloperProfile.vue'

export default {
  name: 'home',
  components: {
    DeveloperProfile
  }
}
</script>