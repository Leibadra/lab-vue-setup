<template>
  <div>
    <input type="checkbox" id="todo-item" />
    <label for="todo-item">My Todo Item</label>
  </div>
  <h1> {{ message }} </h1>
</template>

<script>
export default {
  data() {
    return {
      message: 'To do Item',
    };
  },
};
</script>
