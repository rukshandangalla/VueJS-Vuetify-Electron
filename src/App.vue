<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Eclipse</span>
        <span class="font-weight-light"> Workbench</span>
      </v-toolbar-title>
    </v-toolbar>

    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data() {
    return {
      //
    }
  }
}
</script>
<style>
.headline {
  -webkit-app-region: drag;
}
.headline:hover {
  cursor: move;
}
</style>

