<template>
  <v-card
    class="mx-auto"
    max-width="344"
  >
  <v-card-title>
    Story Title
  </v-card-title>
    <v-card-text>
      <div class="text--primary">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut eu ligula semper, ultrices enim non, porta felis. Maecenas sem ex, pellentesque consectetur libero nec, tristique ornare massa. Nunc eget commodo elit, ut dapibus elit. Integer lorem mauris, tristique a dapibus vel, condimentum sit amet metus. Nullam sed enim id diam vulputate maxim
      </div>
    </v-card-text>
  </v-card>
</template>

<script>
export default {
  name: 'StoryView',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
