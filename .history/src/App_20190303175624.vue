<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
  document.addEventListener('DOMContentLoaded', () => {
    const html = document.querySelector('html')
    let fontSize = window.innerWidth / 10
    html.style.fontSize = fontSize + 'px'
  })
</script>

