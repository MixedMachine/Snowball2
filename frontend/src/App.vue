<template>
  <v-app>
    <v-main>
      <Home/>
    </v-main>
  </v-app>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Home from "./components/HomeContainer.vue";

export default defineComponent({
  name: 'App',

  components: {
    Home,
  },
})
</script>
