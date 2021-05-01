<template>
  <v-card>
    <v-card-title>login</v-card-title>
    <v-card-text>
      <v-text-field label="id" prepend-icon="mdi-account" />
      <v-text-field label="password" type="password" prepend-icon="mdi-lock" />
    </v-card-text>

    <v-card-actions>
      <v-spacer />
      <v-btn id="login" color="primary" class="px-5" @click="login">
        login
      </v-btn>
    </v-card-actions>
  </v-card>
</template>

<script lang="ts">
import { Vue, Component } from 'nuxt-property-decorator'

@Component
export default class LoginForm extends Vue {
  login() {
    console.log('hoge')
  }
}
</script>
