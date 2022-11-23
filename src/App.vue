<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<template>
  <div class="d-flex">

    <div>
      <AppTitle/>
    </div>

    <div>
      <AppHero/>
    </div>
    
  </div>
</template>

<style scoped>
  d-flex{
    display: flex;
    justify-content: center;
  }
</style>
