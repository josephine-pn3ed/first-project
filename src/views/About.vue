<template>
  <div class="about">
    <h3>Developers</h3>
    <DeveloperProfile 
    	v-bind:picture = "require('@/assets/patrick.jpg')" 
    	v-bind:name="'John Patrick Cabia-an'" 
    	v-bind:assign="'(Project Manager)'" 
    	v-bind:description="'He is currently studying at University of San Carlos-Talamban, Cebu City and took the 			course os Certificate of Computer Technology.'"/>

    <DeveloperProfile 
    	v-bind:picture = "require('@/assets/josephine.jpg')" 
    	v-bind:name="'Josephine Morre1'" 
    	v-bind:assign="'(Back-end Developer)'" 
    	v-bind:description="'She is currently studying at University of San Carlos-Talamban, Cebu City and took the 		course os Certificate of Computer Technology.'"/>

    <DeveloperProfile 
    	v-bind:picture = "require('@/assets/burce.jpg')" 
    	v-bind:name="'Jerome Burce'" 
    	v-bind:assign="'(Front-end Developer)'" 
    	v-bind:description="'He is currently studying at University of San Carlos-Talamban, Cebu City and took the 			course os Certificate of Computer Technology.'"/>

    <DeveloperProfile 
    	v-bind:picture = "require('@/assets/irish.jpg')" 
    	v-bind:name="'Irish Rufo'" 
    	v-bind:assign="'(Back-end Developer)'" 
    	v-bind:description="'She is currently studying at University of San Carlos-Talamban, Cebu City and took the 		course os Certificate of Computer Technolog.y'"/>
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

<style>
p {
  margin-left: 0px;
  margin-right: 300px;
  font-family: verdana;
}
</style>