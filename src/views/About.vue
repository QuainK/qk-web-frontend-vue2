<template>
  <div id="main">
    <h1 id="title">QKWeb</h1>
    <div id="content">QuainK 的个人网站</div>
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
