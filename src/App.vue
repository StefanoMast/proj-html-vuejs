<template>
  <div id="app">
    <AppHeader/>
    <AppMain/>
    <AppSection/>
    <AppContactUs/>
    <AppThreeImages/>
    <AppFooter/>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppSection from './components/AppSection.vue';
import AppContactUs from './components/AppContactUs.vue';
import AppThreeImages from './components/AppThreeImages.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain,
    AppSection,
    AppContactUs,
    AppThreeImages,
    AppFooter
}
}
</script>

<style>
@import "./assets/common.sass";


</style>
