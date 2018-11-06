<template>
  <ul id="contents">
    <li>
      <img src="../manga/1.png">
    </li>
    <li>
      <img src="../manga/2.png">
    </li>
    <li>
      <img src="../manga/3.png">
    </li>
    <li>
      <img src="../manga/4.png">
    </li>
    <li>
      <img src="../manga/5.png">
    </li>
    <li>
      <img src="../manga/6.png">
    </li>
    <li>
      <img src="../manga/7.png">
    </li>
    <li>
      <img src="../manga/8.png">
    </li>
  </ul>
</template>

<script>
export default {
  name: 'Manga'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
#contents {
  width: 900px;
  margin: 0 auto;
  text-align: left;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
