<template>
  
<v-app>
    <v-app-bar density="compact">
      <v-app-bar-title>Vuetify</v-app-bar-title>
  
      <v-spacer></v-spacer>
  
      <v-btn text>Developer</v-btn>
  
      <v-btn class="mr-3" text>Help</v-btn>
  
      <v-divider inset vertical></v-divider>
  
      <v-btn
        class="mr-4 ml-5"
        color="primary"
        plain
      >
        <v-icon left icon="mdi-handshake-outline"></v-icon>
  
        <span>เข้าสู่โปรแกรม</span>
      </v-btn>
    </v-app-bar>
  </v-app>
</template>

<script>
export default {
  name : 'indexbar'
}
</script>