<template>

<div v-if="status">Ini tampilkan</div>
<button @click="setStatus">Toggle</button>

<div v-if="status">true</div>
<div v-else-if="status2">false</div>
<div v-else>yg lain</div>
</template>

<script>
  export default {
    data() {
      return {
        status: false,
        status2: true
      }
    },
    methods: {
      setStatus() {
        this.status = !this.status
      }
    }
  }
</script>

<style lang="scss" scoped>

</style>