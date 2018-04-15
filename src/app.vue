<template>
  <div class="showcase-application">
    <showcaseApplication />
  </div>
</template>

<script>
  import showcaseApplication from './components/showcaseApplication.vue'

  export default {
    name: 'app',
    components: {
      showcaseApplication
    }
  };
</script>

<style lang="scss">
  @import 'styles/app';
</style>
