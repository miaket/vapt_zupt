<template>
  <v-toolbar
    app
    color="primary"
    dark
  >
    <v-toolbar-title>List filter</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-btn 
      @click.stop="signOut"
      color="primaryd">
      sign out
    </v-btn>
  </v-toolbar>
</template>

<script>
  export default {
    data(){
      return{}
    },
    methods: {
      signOut() {
        alert("signed out");
      }
    }
  }
</script>
