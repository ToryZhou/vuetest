<template>
  <div id="app" class="base">

    <div id="nav" class="header">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <div class="body">
      <router-view/>
    </div>
    <div class="footer" ref="footer">zzzzzzzzzz</div>
  </div>
</template>

<script>
export default {
  name: 'Hello',
  mounted () {
    console.log(this.$refs.footer)
  }
}
</script>

<style lang="scss" src="./AppStyle.scss">

</style>
