<template>
  <todo-header></todo-header>
  <todo-input></todo-input>
  <todo-list></todo-list>
  <todo-footer></todo-footer>
</template>

<script>
import TodoFooter from './components/TodoFooter.vue'
import TodoHeader from './components/TodoHeader.vue'
import TodoList from './components/TodoList.vue'
import TodoInput from './components/TodoInput.vue';
export default {
  name: 'App',
  components: {
    TodoFooter,TodoHeader,TodoList,TodoInput
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
