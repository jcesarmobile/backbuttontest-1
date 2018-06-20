<template>
  <div id="q-app">
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App',
  methods: {
    onBackButton (e) {
      console.log('Exit Event', e)
    }
  },
  mounted () {
    document.addEventListener('backbutton', this.onBackButton, false)
  }
}
</script>

<style>
</style>
