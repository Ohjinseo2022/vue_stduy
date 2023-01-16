<template>
  <div>
    <div>{{ htmlString }}</div>
    <div v-html="htmlString"></div>
    <!-- 데이터를 html 로 받아올떈 v-html 에 해당하는 키값을 집어넣으면됨 -->
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      htmlString: '<p style="color:red;">HTML 태그 바인딩</p>'
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {}
}
</script>
