<template>
  <v-app>
    <nuxt class="nuxt-content"/>
  </v-app>
</template>
<script>

  export default {

  }
</script>
<style lang="scss">
.layout {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.nuxt-content {
  flex-grow: 1;
}
</style>
