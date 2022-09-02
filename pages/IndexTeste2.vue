<template>
  <div>
    <transition name="home" mode="out-in"></transition>
    <LoadingBar></LoadingBar>
  </div>
</template>

<script>
export default {
  transitions: 'home',
  mounted() {
    this.$nextTick(() => {
      this.$nuxt.$loading.start()
      setTimeout(() => this.$nuxt.$loading.finish(), 500)
    })
  },
  transition: {
    name: 'home',
    mode: 'out-in'
  }
}
</script>

<style>
.home-enter-active, .home-leave-active { transition: opacity .5s; }
.home-enter, .home-leave-active { opacity: 0; }
</style>
