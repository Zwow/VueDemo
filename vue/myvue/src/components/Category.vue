<template>
<div>
  <p id="top">
      {{msg}}
  </p>
</div>
</template>

<script>
export default {
  name: 'Category',
  data () {
    return {
      msg: 'Welcome home'
    }
  }
}
</script>

<style scoped>
#top {
color:aquamarine;
font-size:150%;
}
</style>
