<script>
import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
  // my-component.js
export default {
    data() {
       return { 
        count: 0 
      }
    },
    components:{
    AppHeader,
    AppFooter,
    AppMain
}
}
</script>

<template>
  <div>
  <AppHeader />

  <AppMain />

  <AppFooter />

  </div> 
</template>

<style lang="scss" scoped>
 
</style>
