<template>
  <div>
    <button @click="increaseConuter">Add 1</button>
    <p>{{ conuter }}</p>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      conuter: 0
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {
    increaseConuter() {
      this.conuter += 1
    }
  }
}
</script>
