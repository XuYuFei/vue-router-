<template>
  <div class="main">
    <div class="content">
      <router-view/>
    </div>
    <Navs></Navs>
  </div>
</template>
<script>
import Navs from '@/components/Navs.vue'
export default {
  components: {Navs}
}
</script>
<style>
</style>
