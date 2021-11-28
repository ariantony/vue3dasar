<template>

<div> komponent induk</div>
  
 <anak
  v-for="todo in todos"
  :key="todo"
  :text="todo" />
  
</template>

<script>
import Anak from "./components/Anak.vue"

export default {
    components: { Anak },
    data () {
      return {
          todos: ['pertama','kedua','ketiga']
      }
    }
}

</script>
