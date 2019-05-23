<template>
  <div id="app">
    <nav-bar></nav-bar>
    <transition
    name="page-anim"
    enter-active-class="animated fadeInDown"
    leave-active-class="animated fadeOut"
    mode="out-in"
    appear
    >
      <router-view/>
    </transition>
  </div>
</template>

<script>
import nav from './components/nav'
export default {
  components:{
    'nav-bar':nav
  }
}
</script>

<style>
</style>
