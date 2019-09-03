<template>
  <div class="container">
    <div>
      <Header />
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import Header from '~/components/Header.vue'
@Component({
  components: {
    Header,
  }
})
export default class Index extends Vue {}
</script>

<style>
</style>
