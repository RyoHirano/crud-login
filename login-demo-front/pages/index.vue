<template>
  <v-container>
    <v-row justify="center" align="center">
      <login-form />
    </v-row>
  </v-container>
</template>

<script lang="ts">
import { Vue, Component } from 'nuxt-property-decorator'

@Component
export default class Index extends Vue {}
</script>
