<template>
  <div id="app">
    <the-navbar></the-navbar>
    <div class="main">
      <the-header></the-header>
      <the-content></the-content>
    </div>
  </div>
</template>

<script>
import TheContent from './components/layout/TheContent'
import TheHeader from './components/layout/TheHeader'
import TheNavbar from './components/layout/TheNavbar'
export default {
  components: {
    TheContent,
    TheNavbar,
    TheHeader
  }
}
</script>

<style lang="scss">
@import "./assets/sass/common/main";
#app {
  display: flex;
}

.main {
  flex-grow: 1;
}
</style>
