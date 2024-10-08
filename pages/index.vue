<template lang="pug">

    <NuxtLink to="/TextPage">TextPage</NuxtLink>
</template>

<script>
import Vue from 'vue'
import TextPage from './TextPage/index.vue'

export default Vue.extend({
  name: 'IndexPage',
  components: {
    TextPage, // 注册 TextPage 组件
  }
})
</script>

<style>
a {
  font-weight: 500;
  text-decoration: inherit;
  font-size: 14px;
  color: var(--text-color);
}

a:visited {
  color: var(--text-color);
}

body {
  margin: 0;
  padding: 0;
  height: 100%;
  width: 100%;
  box-sizing: border-box;
}

html {
  overflow-y: scroll;
}
</style>