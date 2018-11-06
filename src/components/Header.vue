<template>
  <header>
    <img class="logo" alt="Vue logo" src="../assets/logo.png">
  </header>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header {
  width: 100%;
  height: 80px;
  background-color: #159588;
  margin: 0 auto;
}

header .logo {
  height: 100%;
}
</style>
