<template>
  <div>
    <AppHeader />
    <AppMain />
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import CardWrapper from './components/CardWrapper.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain,
    CardWrapper
  }
}
</script>

<style lang="scss">
@use './styles/general.scss' as *;
</style>