<template>
  <div id="footer">
    <a href="https://github.com/QuainK">在 Github 上查看</a>
    <p>QKWeb &copy; 2019-2020 QuainK</p>
  </div>
</template>

<script>
  export default {
    name: 'Footer',
  }
</script>

<style scoped>
  #footer {
    display: block;
    width: 100%;
    padding: .5rem 0;
    flex: 0 0 auto;
    background-color: #333;
    color: #ccc;
    font-size: .8rem;
    line-height: 1.5rem;
  }

  #footer a {
    color: #ccc;
  }

  #footer a:hover {
    color: #fff;
  }
</style>
