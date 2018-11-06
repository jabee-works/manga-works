<template>
  <footer>
    Copyright &copy; {{year}} jabee-works All Rights Reserved.
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  data () {
    return {
      year: (new Date()).getFullYear()
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
footer {
  width: 100%;
  height: 80px;
  background-color: #159588;
  color: #ffffff;
  text-align: right;
  margin: 0 auto;
}
</style>
