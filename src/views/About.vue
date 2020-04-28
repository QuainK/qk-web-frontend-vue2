<template>
  <div id="main">
    <div id="title">关于</div>
    <div id="content" class="content-align-center">
      <h1>QKWeb</h1>
      <div class="placeholder"></div>
      <h2>QuainK 的个人网站</h2>
    </div>
  </div>
</template>

<script>
  import Header from '@/components/Header.vue'
  import Footer from '@/components/Footer.vue'

  export default {
    name: 'About',
    title: '关于 About',
    components: {
      Header, Footer
    }
  }
</script>

<style scoped>
  .placeholder {
    margin: 2rem 0;
  }
</style>
