<template>
  <div id="app">
    <div class="container">
      <AddTodo />
      <FilterTodos />
      <TodosVue />
    </div>
  </div>
</template>

<script>
import TodosVue from './components/TodosVue.vue'
import AddTodo from './components/AddTodo.vue'
import FilterTodos from './components/FilterTodos.vue'

export default {
  name: 'App',
  components: {
    TodosVue,
    AddTodo,
    FilterTodos
  }
}
</script>

<style>
body {
  font-family: sans-serif;
  line-height: 1.6;
  background: #e8f7f0;
}
.container {
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>
