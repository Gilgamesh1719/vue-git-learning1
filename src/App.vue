<template>
  <div id="app">
    <h1>Счетчик: {{ count }}</h1>
    <button @click="increment">Увеличить</button>
    <!-- Новая кнопка -->
    <button @click="decrement">Уменьшить</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 0,
    };
  },
  methods: {
    increment() {
      this.count++;
    },
    decrement() {
      this.count--;
    },
  },
};
</script>

<style>
/* Можно оставить пустым или добавить стили по желанию */
</style>