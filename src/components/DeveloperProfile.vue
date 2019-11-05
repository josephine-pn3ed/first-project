<template>
  <b-card>
    <b-row>
      <b-col>
        <img :src="picture" />
      </b-col>
      <b-col>
        <p id="nameId">{{name}}</p>
        <p>{{assign}}</p>
        <p>{{ description }}</p>
      </b-col>
    </b-row>
  </b-card>
</template>
<script>
export default {
  props: {
    name: String,
    picture: String,
    assign: String,
    description: String
  }
};
</script>
<style>
#nameId {
  font-size: 20px;;
}
</style>