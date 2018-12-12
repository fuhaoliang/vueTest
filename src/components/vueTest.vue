<template>
  <div>
    <h1>测试npm发布</h1>
    <h2>props: (msg: {{ msg }})</h2>
  </div>
</template>
<script>
export default {
  name: 'VueTest',
  props: {
    msg: {
      required: false,
      default: 'noProp'
    }
  }
}
</script>
