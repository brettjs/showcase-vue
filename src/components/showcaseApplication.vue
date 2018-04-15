<template>
  <div class="showcase-application">
    <a name="#top"></a>
    <pageHeader />

    <div id="content">
      <!--[if lt IE 10]>
        <p class="browsehappy">You are using an <strong>outdated</strong> browser. Please <a href="http://browsehappy.com/">upgrade your browser</a> to improve your experience.</p>
      <![endif]-->

      <showcaseMaster />
    </div>

    <pageFooter />

  </div>
</template>

<script>
  import pageFooter from './pageFooter.vue'
  import pageHeader from './pageHeader.vue'
  import showcaseMaster from './showcaseMaster.vue'

  export default {
    name: 'app',
    data() {
      return {};
    },
    components: {
      pageFooter,
      pageHeader,
      showcaseMaster
    },
    mounted() {
      fetch('assets/data/en-us.json')
      .then((resp) => (resp.status === 200) ? resp.json() : {})
      .then((data) => {
        this.content = data;
        console.log(data);
      });
    }
  };
</script>

<style lang="scss">
</style>
