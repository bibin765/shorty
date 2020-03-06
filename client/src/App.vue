<template>
  <v-app>
    <v-app-bar
      app
      color="white"
      dark
      hide-on-scroll
    >
      <div class="d-flex align-center">

        <v-img
          alt="Shorty logo"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="120"
          src="./assets/drawing.svg"
          width="100"
        />
      </div>

      <v-spacer></v-spacer>

    </v-app-bar>
    <br /><br /><br /><br />
  <v-container
    align="center"
    justify="center">
    <v-row>
      <v-col>
        <story-view />
      </v-col>
      <v-col>
        <story-view />
      </v-col>
      <v-col>
        <story-view />
      </v-col>
      <v-col>
        <story-view />
      </v-col>    
    </v-row>
    <v-row>
        <v-col>
          <story-view />
        </v-col> 
        <v-col>
          <story-view />
        </v-col> 
        <v-col>
          <story-view />
        </v-col> 
        <v-col>
          <story-view />
        </v-col> 
    </v-row>
  </v-container>
</v-app>
</template>

<script>
import StoryView from './components/StoryView';

export default {
  name: 'App',

  components: {
    StoryView,
  },

  data: () => ({
    //
  }),
};
</script>

<style>

</style>
