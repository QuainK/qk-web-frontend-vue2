<template>
  <div id="main">
    <div id="content">
      <h1>QKWeb</h1><br><br><br>
      <h2>QuainK 的个人网站</h2><br><br><br>
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
