<template>
  <div id="main">
    <div class="item">
      <div class="item-img">
        <router-link to="/works/BDHConverter">
          <img alt="进制转换器 BDHConverter" src="@/assets/img/svg/calculator.svg">
        </router-link>
      </div>
      <p>进制转换器</p>
      <p>BDHConverter</p>
    </div>
    <div class="item">
      <div class="item-img">
        <router-link to="/works/So">
          <img alt="搜索引擎整合 So" src="@/assets/img/svg/search.svg">
        </router-link>
      </div>
      <p>搜索引擎整合</p>
      <p>So</p>
    </div>
    <div class="item">
      <div class="item-img">
        <router-link to="/works/GuessNumber">
          <img alt="猜数 GuessNumber" src="@/assets/img/svg/game.svg">
        </router-link>
      </div>
      <p>猜数</p>
      <p>GuessNumber</p>
    </div>
  </div>
</template>

<script>
  import Header from '@/components/Header.vue'
  import Footer from '@/components/Footer.vue'

  export default {
    name: 'Works',
    title: '作品 Works',
    components: {
      Header, Footer
    }
  }
</script>
