<template>
  <div class="home">
    <div id="read"></div>
  </div>
</template>

<script>
import Epub from 'epubjs'
global.epub = Epub
export default {
  name:'home',
  mounted () {
    this.book
  }
}
</script>
