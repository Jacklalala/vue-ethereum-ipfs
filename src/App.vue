<template>
  <div id="app">
    <transition
      name="fade"
      mode="out-in"
    >
      <router-view class="view" />
    </transition>
  </div>
</template>

<script>
export default {}
</script>

<style lang="sass">
  @import "~bulma"
  html, body
    overflow-y: auto
    width: 100vw
    height: 100vh
</style>
