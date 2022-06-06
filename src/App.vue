<template>
<HeaderBar></HeaderBar>
  <p>Welcome to my website</p>
</template>

<script>
import HeaderBar from "./components/HeaderBar.vue";

export default {
  name: 'App',
  components: {
    HeaderBar
  }
}
</script>

<style lang="scss">
@import "@/assets/styles/_variables.scss";
</style>
