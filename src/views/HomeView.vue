<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <h2>Welcome to Your Vue.js + TypeScript App</h2>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  components: {},
})
export default class HomeView extends Vue {}
</script>
