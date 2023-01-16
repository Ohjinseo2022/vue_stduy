<template>
  <div>
    <h1>Hello {{ userName }}</h1>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      userName: 'John Doe',
      message: 'Welcome',
      arr: [],
      abj: {}
    }
  }
}
</script>

<style scoped>
/* 개별화면에 적용하는 css  */
</style>
