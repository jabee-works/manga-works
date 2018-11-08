<template>
    <ul id="contents">
      <li v-for="item in list"><img v-bind:src="'' + item.img + ''"></li>
    </ul>
</template>

import Vue from 'vue'
<script>
export default {
  name: 'Manga',
  data: function(){
      return {
      list: [
        { img: require('../manga/1.png') },
        { img: require('../manga/2.png') },
        { img: require('../manga/3.png') },
        { img: require('../manga/4.png') },
        { img: require('../manga/5.png') },
        { img: require('../manga/6.png') },
        { img: require('../manga/7.png') },
        { img: require('../manga/8.png') },
        { img: require('../manga/9.png') }
      ]
    }
  }
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
