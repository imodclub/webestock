<template>
  <v-app>
    <v-main>
      <getadmin/>
    </v-main>
  </v-app>
</template>

<script>
import getadmin from './components/getadmin.vue'

export default {
  name: 'App',

  components: {
    getadmin,
  },

  data: () => ({
    //
  }),
}
</script>
