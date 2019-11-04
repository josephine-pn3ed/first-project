<template>
  <div class="about">
    <h1>Developers</h1>
    <DeveloperProfile v-bind:picture = "require('@/assets/josephine.jpg')" v-bind:name="'Josephine Morre'" v-bind:assign="'(Back-end Developer)'"></DeveloperProfile>
    <DeveloperProfile v-bind:picture = "require('@/assets/patrick.jpg')" v-bind:name="'John Patrick Cabia-an'" v-bind:assign="'(Project Manager)'"></DeveloperProfile>
    <DeveloperProfile v-bind:picture = "require('@/assets/burce.jpg')" v-bind:name="'Jerome Burce'" v-bind:assign="'(Front-end Developer)'"></DeveloperProfile>
    <DeveloperProfile v-bind:picture = "require('@/assets/irish.jpg')" v-bind:name="'Irish Rufo'" v-bind:assign="'(Back-end Developer)'"></DeveloperProfile>
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