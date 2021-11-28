<template>

 <div>{{ message }}</div>
<input v-model="message">

</template>

<script>
  export default {
    data() {
      return {
        message: 'hai'
      }
    }
  }
</script>

<style lang="scss" scoped>

</style>