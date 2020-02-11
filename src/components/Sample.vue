<template>
  <div class="Sample">
    <p>hello {{ name }}!</p>
    <p><input type="text" v-model="name"></p>
    <ul>
        <li>{{ todos[0] }}</li>
        <li>{{ todos[1] }}</li>
        <li>{{ todos[2] }}</li>
        <li v-for="(todo, key) in todos" v-bind:key="key">{{ todo }}</li>
        <input type="text">
        <input type="submit" value="Add">
    </ul>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Start',
  data: () => ({
    name: 'hello',
    todos: [
      'task 1',
      'task 2',
      'task 3'
    ]
  })
}
</script>
