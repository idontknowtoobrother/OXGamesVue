<template>
  <div>
    <h1>MyPage</h1>
    <h3> {{ name }}</h3>
    <img src="../assets/myImg.gif" alt="">
  </div>
</template>
<script>
export default {
  props: ['name']
}
</script>
<style>
</style>
