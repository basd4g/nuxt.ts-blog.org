<template>
  <div id="nuxt-ts-blog--header">
      {{message}}
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
export default class Header extends Vue {
    message: String = "This is Header"
}
</script>

<style></style>
