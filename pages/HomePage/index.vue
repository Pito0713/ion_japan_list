<template lang="pug">
<a>HomePage</a>
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
  name: 'HomePage',
  components: {
  },
  data() {
    return {
      textarea: '',
      reverse: true,
      activities: [{
        content: '活动按期开始',
        timestamp: '2018-04-15'
      }, {
        content: '通过审核',
        timestamp: '2018-04-13'
      }, {
        content: '创建成功',
        timestamp: '2018-04-11'
      }]
    }
  },
  methods: {
    clearTextarea() {
      this.textarea = '';
    }
  }
})
</script>