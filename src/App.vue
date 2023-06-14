<script>
import HelloWorld from './components/HelloWorld.vue'
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'
import AppHeader from './components/AppHeader.vue'

export default{
  components:{
    AppTitle,
    AppHero,
    AppHeader
  }
}
</script>

<template>
    <AppHeader/>
    <AppHero/>
    <AppTitle/>
</template>

<style scoped>

</style>
