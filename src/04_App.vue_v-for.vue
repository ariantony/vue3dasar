<template>
<ol>
  <li v-for="todo in todos" :key="todo.id">{{todo.activity}}</li>
</ol>
<hr>
<ol>
  <li v-for="(todo, index) in todos" :key="todo.id">
    {{ index }} - {{todo.activity}}
    </li>
</ol>
</template>

<script>
  export default {
    data() {
      return {
        todos: [
          { id: 1, activity: 'Menyapu'},
          { id: 2, activity: 'Ngepel'},
          { id: 3, activity: 'Masak'},
        ]
      }
    }
  }
</script>

<style lang="scss" scoped>

</style>