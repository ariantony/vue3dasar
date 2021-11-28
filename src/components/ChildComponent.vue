<template>
    <div>
        ini component anak 2
        {{ text1 }}
    </div>
</template>

<script>
    export default {
       props: {
           text1: {
               type: String,
               default: ''
           }
       } 
    }
</script>

<style lang="scss" scoped>

</style>