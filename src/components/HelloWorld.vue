<template>
  <v-container>
    <v-card class="">
      <v-toolbar dark color="primary">
        <v-toolbar-title>Login form</v-toolbar-title>
      </v-toolbar>
      <v-card-text>
        <v-form>
          <v-text-field prepend-icon="person" name="login" label="Login" type="text"></v-text-field>
          <v-text-field prepend-icon="lock" name="password" label="Password" id="password" type="password"></v-text-field>
        </v-form>
      </v-card-text>
      <v-card-actions>
        <v-spacer></v-spacer>
        <v-btn color="primary">Login</v-btn>
      </v-card-actions>
    </v-card>
  </v-container>
</template>

<script>
  export default {
    
  }
</script>

<style>

</style>
