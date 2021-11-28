<template>

 <div>{{ count }}</div>

<button @click="count++"> add 1</button>
<button @click="addCount"> AddCount </button>
</template>

<script>
  export default {
    data() {
      return {
        count: 0
      }
    },
    methods: {
      addCount() {
        this.count += 2;
      }
    }
  }
</script>

<style lang="scss" scoped>

</style>