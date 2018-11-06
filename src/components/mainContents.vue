<template>
  <div>
    <h1>mainContents</h1>
    
    <Manga />
  </div>
</template>

<script>
import Manga from './Manga.vue'

export default {
  name: 'mainContents',
  props: {
    msg: String
  },
  components: {
    Manga
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
