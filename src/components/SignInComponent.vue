<template>
  <v-container>
    <v-row no-gutters>
      <v-col md="6">
        <h1>Test</h1>
      </v-col>

      <v-col md="4">
        <v-card max-width class="login-card text-center py-5 px-3">
          <h3 class="display-1 mt-3">StartUp Invest</h3>
          <v-card-text>
            <v-text-field
              label="E-mail"
              v-model="email"
              outlined
              required
              class="mt-5"
              color="#B2DFDB"
              autofocus
            ></v-text-field>
            <v-text-field label="Senha" v-model="senha" outlined required color="#B2DFDB" autofocus></v-text-field>
          </v-card-text>
          <v-card-actions>
            <v-btn block color="#B2DFDB" dark>Block Button</v-btn>
          </v-card-actions>
        </v-card>
      </v-col>

      <v-col md="2"></v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  data: () => ({})
};
</script>

<style scoped>
.login-card {
  margin-top: 100px;
}
</style>
