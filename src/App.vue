<template lang="jade">
  div#app
    img.log(src="./assets/logo.png")
    hello
</template>

<script>
import Hello from './components/Hello'

export default {
  components: {
    Hello
  }
}
</script>

<style lang="sass">
body {
  font-family: Helvetica, sans-serif;
}

#app {
  img {
    float: right;
  }
}
</style>
