<script>
import './styles/general.scss'
import AppHeader from './components/AppHeader.vue'

export default{
  components:{
    AppHeader
  }
}
</script>


<template>
    <AppHeader/>
</template>

<style lang="scss">
@use '../src/styles/general.scss' as * ;
@import "./bootstrap/scss/bootstrap";


</style>
