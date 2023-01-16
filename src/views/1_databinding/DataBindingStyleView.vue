<template>
  <div>
    <div style="color: red; font-size: 30px">
      스타일 바인딩 : 클씨는 red, 폰트크기: 30px
    </div>
    <div :style="style1">스타일 바인딩 : 클씨는 green, 폰트크기: 30px</div>
    <button @click="colorHandler">클릭</button>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      colorCheck: false,
      style1: {
        color: 'green',
        fontSize: '30px'
      }
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {
    colorHandler() {
      this.colorCheck = !this.colorCheck
      this.colorCheck === false
        ? (this.style1.color = 'green')
        : (this.style1.color = 'blue')
    }
  }
}
</script>
