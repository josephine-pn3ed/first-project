<template>
  <v-card>
    <v-row>
      <v-col>
        <img :src="picture" />
      </v-col>
      <v-col cols='10' class="text-left">
        <h1>{{name}}</h1>
        <h3>{{assign}}</h3>
      </v-col>
    </v-row>
  </v-card>
</template>
<script>
export default {
  props: {
    name: String,
    picture: String,
    assign: String
  }
};
</script>