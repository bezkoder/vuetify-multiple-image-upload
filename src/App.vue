<template>
  <v-app>
    <v-container fluid style="width: 600px">
      <div class="mb-5">
        <h1>bezkoder.com</h1>
        <h2>Vuetify multiple Images upload</h2>
      </div>

      <upload-images></upload-images>
    </v-container>
  </v-app>
</template>

<script>
import UploadImages from "./components/UploadImages";

export default {
  name: "App",
  components: {
    UploadImages,
  },
};
</script>
