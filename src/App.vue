<template>
  <div id="app">
    <!-- 路由出口，删了就看不见页面了 -->
    <router-view/>
    <h1>仿头条</h1>
    <div>
      <i class="toutiao toutiao-shipin"></i>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="less">
</style>
