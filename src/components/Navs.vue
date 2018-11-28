<template>
  <div class="navs">
    <ul>
        <router-link :to="{ name: 'home' }" tag="li" replace exact>首页</router-link>
        <router-link :to="{ name: 'category' }" tag="li" replace>分类</router-link>
        <router-link :to="{ name: 'cart' }" tag="li" replace>购物车</router-link>
        <router-link :to="{ name: 'me' }" tag="li" replace>我</router-link>
    </ul>
  </div>
</template>
<script>
import './Navs.less'
export default {}
</script>
